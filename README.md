# Desain-Web
coding bootstrap CSS index.html pb 6

<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nui Creative - Digital Agency</title>

    <!-- Bootstrap 5 CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f8f9fa;
        }

        /* Navbar */
        .navbar {
            background-color: #183153;
        }

        .navbar-brand {
            font-weight: bold;
            color: white;
        }

        .navbar-brand:hover {
            color: #dbeafe;
        }

        .nav-link {
            color: white;
        }

        .nav-link:hover {
            color: #93c5fd;
        }

        /* Hero */
        .hero {
            background: linear-gradient(rgba(24, 49, 83, 0.75),
            rgba(24, 49, 83, 0.75)),
            url("https://images.unsplash.com/photo-1497366754035-f200968a6e72");
            background-size: cover;
            background-position: center;
            padding: 110px 20px;
            color: white;
        }

        .hero h1 {
            font-weight: bold;
        }

        /* Judul Section */
        .section-title {
            color: #183153;
            font-weight: bold;
        }

        /* Card */
        .service-card {
            border: none;
            border-radius: 12px;
            transition: 0.3s;
        }

        .service-card:hover {
            transform: translateY(-7px);
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.15);
        }

        .service-card img {
            height: 190px;
            object-fit: cover;
            border-radius: 12px 12px 0 0;
        }

        .service-price {
            color: #183153;
            font-size: 20px;
            font-weight: bold;
        }

        /* Button */
        .btn-nui {
            background-color: #183153;
            color: white;
            border: none;
        }

        .btn-nui:hover {
            background-color: #294d7a;
            color: white;
        }

        /* Form Kontak */
        .contact-box {
            background-color: white;
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 3px 12px rgba(0, 0, 0, 0.08);
        }

        /* Footer */
        footer {
            background-color: #183153;
            color: white;
        }

        /* Tampilan Smartphone */
        @media (max-width: 576px) {
            .hero {
                padding: 75px 15px;
            }

            .hero h1 {
                font-size: 28px;
            }

            .service-card img {
                height: 200px;
            }
        }
    </style>
</head>

<body>

    <!-- 1. NAVBAR -->
    <nav class="navbar navbar-expand-lg navbar-dark">
        <div class="container">
            <a class="navbar-brand" href="#home">
                Nui Creative
            </a>
            <button class="navbar-toggler" type="button"
                data-bs-toggle="collapse" data-bs-target="#menuNavbar">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="menuNavbar">
                <ul class="navbar-nav ms-auto">

                    <li class="nav-item">
                        <a class="nav-link" href="#home">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#tentang">Tentang Kami</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#layanan">Layanan</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#kontak">Kontak</a>
                    </li>
                </ul>
            </div>

        </div>
    </nav>

    <!-- 2. HERO SECTION -->
    <section id="home" class="hero text-center">

        <div class="container">

            <span class="badge bg-light text-primary mb-3 p-2">
                Digital Creative Agency
            </span>

            <h1 class="display-5">
                Selamat Datang di Nui Creative
            </h1>

            <p class="lead mt-3">
                Membantu bisnis berkembang melalui teknologi digital
                dan kreativitas tanpa batas.
            </p>

            <a href="#layanan" class="btn btn-light mt-3 px-4">
                Lihat Layanan
            </a>

        </div>

    </section>

    <!-- 3. TENTANG KAMI -->
    <section id="tentang" class="container py-5 text-center">

        <h2 class="section-title mb-3">
            Tentang Kami
        </h2>

        <p class="text-secondary mx-auto" style="max-width: 750px;">
            Nui Creative merupakan penyedia layanan digital yang
            membantu pelaku usaha dalam mengembangkan bisnis melalui
            teknologi, kreativitas, dan strategi digital.
        </p>

    </section>

    <!-- 4. LAYANAN KAMI -->
    <section id="layanan" class="container py-5">

        <div class="text-center mb-5">

            <h2 class="section-title">
                Layanan Kami
            </h2>

            <p class="text-secondary">
                Temukan solusi digital untuk kebutuhan bisnis Anda.
            </p>

        </div>

        <!-- Bootstrap Grid -->
        <div class="row g-4">
            <!-- Card 1 -->
            <div class="col-12 col-md-6 col-lg-3">
                <div class="card service-card h-100">
                    <img src="https://images.unsplash.com/photo-1460925895917-afdab827c52f"
                        class="card-img-top" alt="Desain Website">
                    <div class="card-body text-center">
                        <span class="badge bg-primary mb-2">
                            Website
                        </span>
                        <h5 class="card-title fw-bold">
                            Desain Website
                        </h5>
                        <p class="card-text text-secondary small">
                            Membuat website yang menarik, modern,
                            dan mudah digunakan.
                        </p>
                        <p class="service-price">
                            Rp1.500.000
                        </p>
                        <a href="#kontak" class="btn btn-nui w-100">
                            Pesan Sekarang
                        </a>
                    </div>
                </div>
            </div>

            <!-- Card 2 -->
            <div class="col-12 col-md-6 col-lg-3">

                <div class="card service-card h-100">

                    <img src="https://images.unsplash.com/photo-1432888622747-4eb9a8efeb07"
                        class="card-img-top" alt="Digital Marketing">

                    <div class="card-body text-center">

                        <span class="badge bg-success mb-2">
                            Marketing
                        </span>

                        <h5 class="card-title fw-bold">
                            Digital Marketing
                        </h5>

                        <p class="card-text text-secondary small">
                            Membantu promosi bisnis melalui media
                            sosial dan platform digital.
                        </p>

                        <p class="service-price">
                            Rp750.000
                        </p>

                        <a href="#kontak" class="btn btn-nui w-100">
                            Pesan Sekarang
                        </a>

                    </div>
                </div>

            </div>

            <!-- Card 3 -->
            <div class="col-12 col-md-6 col-lg-3">

                <div class="card service-card h-100">

                    <img src="https://images.unsplash.com/photo-1556761175-b413da4baf72"
                        class="card-img-top" alt="Konsultasi Bisnis">

                    <div class="card-body text-center">

                        <span class="badge bg-warning text-dark mb-2">
                            Business
                        </span>

                        <h5 class="card-title fw-bold">
                            Konsultasi Bisnis
                        </h5>

                        <p class="card-text text-secondary small">
                            Memberikan solusi dan strategi
                            untuk mengembangkan usaha.
                        </p>

                        <p class="service-price">
                            Rp500.000
                        </p>

                        <a href="#kontak" class="btn btn-nui w-100">
                            Pesan Sekarang
                        </a>

                    </div>
                </div>

            </div>

            <!-- Card 4 -->
            <div class="col-12 col-md-6 col-lg-3">

                <div class="card service-card h-100">

                    <img src="https://images.unsplash.com/photo-1545235617-9465d2a55698"
                        class="card-img-top" alt="Desain Grafis">

                    <div class="card-body text-center">

                        <span class="badge bg-danger mb-2">
                            Creative
                        </span>

                        <h5 class="card-title fw-bold">
                            Desain Grafis
                        </h5>

                        <p class="card-text text-secondary small">
                            Membuat desain visual untuk kebutuhan
                            promosi dan identitas bisnis.
                        </p>

                        <p class="service-price">
                            Rp300.000
                        </p>

                        <a href="#kontak" class="btn btn-nui w-100">
                            Pesan Sekarang
                        </a>

                    </div>
                </div>

            </div>

        </div>
    </section>

    <!-- 5. FORM KONTAK -->
    <section id="kontak" class="container py-5">
        <div class="text-center mb-4">
            <h2 class="section-title">
                Hubungi Kami
            </h2>
            <p class="text-secondary">
                Silakan isi formulir untuk menghubungi Nui Creative.
            </p>
        </div>
        <div class="row justify-content-center">
            <div class="col-12 col-md-10 col-lg-7">
                <div class="contact-box">
                    <form>
                        <div class="mb-3">
                            <label class="form-label">
                                Nama
                            </label>
                            <input type="text" class="form-control"
                                placeholder="Masukkan nama Anda">
                        </div>
                        <div class="mb-3">
                            <label class="form-label">
                                Email
                            </label>
                            <input type="email" class="form-control"
                                placeholder="Masukkan email Anda">
                        </div>
                        <div class="mb-3">
                            <label class="form-label">
                                Pesan
                            </label>
                            <textarea class="form-control" rows="4"
                                placeholder="Tulis pesan Anda"></textarea>
                        </div>
                        <button type="submit" class="btn btn-nui">
                            Kirim Pesan
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- 6. FOOTER -->
    <footer class="text-center py-4">
        <p class="mb-0">
            © 2026 Nui Creative. All Rights Reserved.
        </p>
    </footer>
    <!-- Bootstrap 5 JavaScript -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
