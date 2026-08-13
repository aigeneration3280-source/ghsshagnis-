<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Govt. Girls Higher Secondary School Hagnis, Kargil | UT Ladakh - 194109</title>
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@600;700;800&family=Plus+Jakarta+Sans:wght@300;400;500;600;700&display=swap" rel="stylesheet">

    <style>
        :root {
            --primary-navy: #0F2C59;
            --primary-blue: #1E3E62;
            --secondary-teal: #00A896;
            --accent-gold: #F4A261;
            --accent-orange: #E76F51;
            --bg-light: #F8F9FA;
            --surface-white: #FFFFFF;
            --text-dark: #2B2D42;
            --text-muted: #6C757D;
            --border-color: #E9ECEF;
            --ladakh-red: #8B0000;
            --radius-sm: 6px;
            --radius-md: 12px;
            --radius-lg: 20px;
            --shadow-sm: 0 2px 8px rgba(0,0,0,0.06);
            --shadow-md: 0 6px 16px rgba(0,0,0,0.1);
            --shadow-lg: 0 12px 32px rgba(0,0,0,0.15);
            --transition: all 0.3s cubic-bezier(0.25, 0.8, 0.25, 1);
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: 'Plus Jakarta Sans', sans-serif;
            color: var(--text-dark);
            background-color: var(--bg-light);
            line-height: 1.6;
            overflow-x: hidden;
        }

        h1, h2, h3, h4, h5, .brand-font {
            font-family: 'Cinzel', serif;
        }

        a {
            text-decoration: none;
            color: inherit;
        }

        ul {
            list-style: none;
        }

        img {
            max-width: 100%;
            height: auto;
            display: block;
        }

        /* Utility Classes */
        .container {
            width: 100%;
            max-width: 1280px;
            margin: 0 auto;
            padding: 0 1.5rem;
        }

        .btn {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            gap: 0.5rem;
            padding: 0.75rem 1.5rem;
            border-radius: var(--radius-sm);
            font-weight: 600;
            cursor: pointer;
            transition: var(--transition);
            border: none;
            font-size: 0.95rem;
        }

        .btn-primary {
            background-color: var(--primary-navy);
            color: var(--surface-white);
        }

        .btn-primary:hover {
            background-color: var(--secondary-teal);
            transform: translateY(-2px);
        }

        .btn-accent {
            background-color: var(--accent-gold);
            color: var(--primary-navy);
        }

        .btn-accent:hover {
            background-color: var(--accent-orange);
            color: var(--surface-white);
            transform: translateY(-2px);
        }

        .btn-outline {
            background: transparent;
            border: 2px solid var(--primary-navy);
            color: var(--primary-navy);
        }

        .btn-outline:hover {
            background: var(--primary-navy);
            color: var(--surface-white);
        }

        .btn-danger {
            background-color: #D32F2F;
            color: #FFF;
        }

        .btn-danger:hover {
            background-color: #9A0007;
        }

        .btn-sm {
            padding: 0.3rem 0.7rem;
            font-size: 0.75rem;
        }

        .section-padding {
            padding: 5rem 0;
        }

        .section-header {
            text-align: center;
            margin-bottom: 3.5rem;
            position: relative;
        }

        .section-header h2 {
            font-size: 2.25rem;
            color: var(--primary-navy);
            margin-bottom: 0.75rem;
            position: relative;
            display: inline-block;
        }

        .section-header h2::after {
            content: '';
            position: absolute;
            bottom: -10px;
            left: 50%;
            transform: translateX(-50%);
            width: 80px;
            height: 4px;
            background: linear-gradient(90deg, var(--secondary-teal), var(--accent-gold));
            border-radius: 2px;
        }

        .section-header p {
            color: var(--text-muted);
            font-size: 1.05rem;
            max-width: 650px;
            margin: 0.75rem auto 0;
        }

        /* Cultural Pattern Border Top */
        .ladakh-border-top {
            border-top: 5px solid var(--ladakh-red);
            position: relative;
        }
        .ladakh-border-top::before {
            content: '';
            position: absolute;
            top: -5px;
            left: 0;
            right: 0;
            height: 5px;
            background: repeating-linear-gradient(
                90deg,
                var(--accent-gold),
                var(--accent-gold) 15px,
                var(--secondary-teal) 15px,
                var(--secondary-teal) 30px,
                var(--ladakh-red) 30px,
                var(--ladakh-red) 45px
            );
        }

        /* Top Bar */
        .top-bar {
            background-color: var(--primary-navy);
            color: rgba(255,255,255,0.85);
            font-size: 0.85rem;
            padding: 0.5rem 0;
            border-bottom: 1px solid rgba(255,255,255,0.1);
        }

        .top-bar-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .top-bar-info {
            display: flex;
            gap: 1.5rem;
        }

        .top-bar-info span {
            display: flex;
            align-items: center;
            gap: 0.4rem;
        }

        .top-bar-actions {
            display: flex;
            gap: 1rem;
            align-items: center;
        }

        /* Header */
        .main-header {
            background: var(--surface-white);
            box-shadow: var(--shadow-sm);
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        .header-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 1rem 0;
        }

        .brand-container {
            display: flex;
            align-items: center;
            gap: 1.25rem;
        }

        .school-logo {
            width: 92px;
            height: 92px;
            background: var(--primary-navy);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--accent-gold);
            font-size: 2.6rem;
            border: 3px solid var(--accent-gold);
            flex-shrink: 0;
            overflow: hidden;
        }

        .school-logo img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        .brand-text h1 {
            font-size: 1.2rem;
            color: var(--primary-navy);
            line-height: 1.2;
            font-weight: 700;
        }

        .brand-text .location {
            font-size: 0.85rem;
            color: var(--text-muted);
            margin-top: 0.2rem;
        }

        .header-actions {
            display: flex;
            align-items: center;
            gap: 1rem;
        }

        /* Navigation */
        .nav-bar {
            background: var(--primary-blue);
            border-top: 1px solid rgba(255,255,255,0.1);
        }

        .nav-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .nav-menu {
            display: flex;
            flex-wrap: wrap;
        }

        .nav-item {
            position: relative;
        }

        .nav-link {
            display: block;
            padding: 1rem 1.1rem;
            color: var(--surface-white);
            font-size: 0.88rem;
            font-weight: 500;
            letter-spacing: 0.3px;
            transition: var(--transition);
        }

        .nav-link:hover, .nav-link.active {
            background-color: var(--secondary-teal);
            color: var(--surface-white);
        }

        .mobile-toggle {
            display: none;
            background: none;
            border: none;
            color: var(--primary-navy);
            font-size: 1.5rem;
            cursor: pointer;
        }

        /* Ticker Bar */
        .ticker-bar {
            background: var(--accent-gold);
            color: var(--primary-navy);
            display: flex;
            align-items: center;
            font-weight: 600;
            font-size: 0.9rem;
            overflow: hidden;
        }

        .ticker-title {
            background: var(--accent-orange);
            color: var(--surface-white);
            padding: 0.6rem 1.25rem;
            white-space: nowrap;
            display: flex;
            align-items: center;
            gap: 0.5rem;
            font-size: 0.85rem;
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }

        .ticker-content {
            padding: 0.5rem 1rem;
            white-space: nowrap;
            animation: ticker 25s linear infinite;
        }

        .ticker-content:hover {
            animation-play-state: paused;
        }

        @keyframes ticker {
            0% { transform: translateX(100%); }
            100% { transform: translateX(-100%); }
        }

        /* Hero Section */
        .hero {
            position: relative;
            min-height: 80vh;
            background: linear-gradient(rgba(15, 44, 89, 0.75), rgba(15, 44, 89, 0.85)), url('https://images.unsplash.com/photo-1509062522246-3755977927d7?q=80&w=1600&auto=format&fit=crop') center/cover no-repeat;
            display: flex;
            align-items: center;
            color: var(--surface-white);
            padding: 4rem 0;
        }

        .hero-content {
            max-width: 850px;
        }

        .hero-badge {
            display: inline-block;
            padding: 0.4rem 1rem;
            background: rgba(0, 168, 150, 0.3);
            border: 1px solid var(--secondary-teal);
            border-radius: 50px;
            font-size: 0.85rem;
            color: #A5F3FC;
            margin-bottom: 1.5rem;
            backdrop-filter: blur(4px);
        }

        .hero h1 {
            font-size: 2.8rem;
            line-height: 1.2;
            margin-bottom: 1.25rem;
            color: var(--surface-white);
        }

        .hero p {
            font-size: 1.2rem;
            margin-bottom: 2rem;
            color: rgba(255,255,255,0.9);
            font-weight: 300;
        }

        .hero-buttons {
            display: flex;
            gap: 1rem;
            flex-wrap: wrap;
        }

        /* Quick Stats Grid */
        .stats-section {
            margin-top: -4rem;
            position: relative;
            z-index: 10;
        }

        .stats-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 1.5rem;
        }

        .stat-card {
            background: var(--surface-white);
            padding: 2rem 1.5rem;
            border-radius: var(--radius-md);
            box-shadow: var(--shadow-md);
            text-align: center;
            border-bottom: 4px solid var(--secondary-teal);
            transition: var(--transition);
        }

        .stat-card:hover {
            transform: translateY(-5px);
            box-shadow: var(--shadow-lg);
        }

        .stat-icon {
            font-size: 2.25rem;
            color: var(--primary-navy);
            margin-bottom: 0.75rem;
        }

        .stat-number {
            font-size: 2rem;
            font-weight: 700;
            color: var(--primary-navy);
            font-family: 'Cinzel', serif;
        }

        .stat-label {
            color: var(--text-muted);
            font-size: 0.9rem;
            margin-top: 0.25rem;
        }

        /* Grid Layouts */
        .grid-2 {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 2.5rem;
        }

        .grid-3 {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 2rem;
        }

        .grid-4 {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 1.5rem;
        }

        /* Cards */
        .card {
            background: var(--surface-white);
            border-radius: var(--radius-md);
            overflow: hidden;
            box-shadow: var(--shadow-sm);
            border: 1px solid var(--border-color);
            transition: var(--transition);
        }

        .card:hover {
            box-shadow: var(--shadow-md);
            transform: translateY(-3px);
        }

        .card-body {
            padding: 1.75rem;
        }

        /* Notice Board Component */
        .notice-card {
            display: flex;
            gap: 1.25rem;
            padding: 1.25rem;
            border-bottom: 1px solid var(--border-color);
            background: var(--surface-white);
            transition: var(--transition);
            align-items: flex-start;
        }

        .notice-card:hover {
            background: #F0F7FF;
        }

        .notice-date {
            background: var(--primary-navy);
            color: var(--surface-white);
            padding: 0.5rem 0.75rem;
            border-radius: var(--radius-sm);
            text-align: center;
            min-width: 65px;
            height: fit-content;
        }

        .notice-date .day {
            font-size: 1.25rem;
            font-weight: 700;
            line-height: 1;
        }

        .notice-date .month {
            font-size: 0.7rem;
            text-transform: uppercase;
            margin-top: 0.2rem;
        }

        .notice-info {
            flex-grow: 1;
        }

        .notice-info h4 {
            font-size: 1rem;
            margin-bottom: 0.4rem;
            color: var(--primary-navy);
        }

        .notice-info p {
            font-size: 0.85rem;
            color: var(--text-muted);
            margin-bottom: 0.5rem;
        }

        .notice-image {
            width: 100%;
            max-width: 220px;
            border-radius: var(--radius-sm);
            margin: 0.5rem 0;
        }

        .notice-badge {
            font-size: 0.7rem;
            padding: 0.2rem 0.5rem;
            border-radius: 4px;
            font-weight: 600;
            text-transform: uppercase;
            display: inline-block;
            margin-bottom: 0.3rem;
        }

        .badge-urgent { background: #FFE3E3; color: #D00000; }
        .badge-academic { background: #E3F2FD; color: #0D47A1; }
        .badge-general { background: #E8F5E9; color: #1B5E20; }

        /* Faculty Cards */
        .faculty-card {
            text-align: center;
            position: relative;
        }

        .faculty-img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            margin: 0 auto 1.25rem;
            object-fit: cover;
            border: 4px solid var(--bg-light);
            box-shadow: var(--shadow-sm);
        }

        .faculty-card h3 {
            font-size: 1.1rem;
            color: var(--primary-navy);
        }

        .faculty-card .designation {
            color: var(--secondary-teal);
            font-weight: 600;
            font-size: 0.88rem;
            margin-bottom: 0.5rem;
        }

        .faculty-card .meta {
            font-size: 0.8rem;
            color: var(--text-muted);
        }

        /* Facility image */
        .facility-img {
            width: 100%;
            height: 150px;
            object-fit: cover;
            border-radius: var(--radius-sm);
            margin-bottom: 0.75rem;
        }

        /* Gallery Grid */
        .gallery-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(260px, 1fr));
            gap: 1.25rem;
        }

        .gallery-item {
            position: relative;
            border-radius: var(--radius-sm);
            overflow: hidden;
            height: 200px;
            cursor: pointer;
        }

        .gallery-item img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: var(--transition);
        }

        .gallery-item:hover img {
            transform: scale(1.08);
        }

        .gallery-overlay {
            position: absolute;
            inset: 0;
            background: rgba(15, 44, 89, 0.7);
            color: var(--surface-white);
            display: flex;
            flex-direction: column;
            justify-content: flex-end;
            padding: 1rem;
            opacity: 0;
            transition: var(--transition);
        }

        .gallery-item:hover .gallery-overlay {
            opacity: 1;
        }

        /* Modals */
        .modal-overlay {
            position: fixed;
            inset: 0;
            background: rgba(0, 0, 0, 0.65);
            display: flex;
            align-items: center;
            justify-content: center;
            z-index: 2000;
            padding: 1.5rem;
            opacity: 0;
            visibility: hidden;
            transition: var(--transition);
        }

        .modal-overlay.active {
            opacity: 1;
            visibility: visible;
        }

        .modal-card {
            background: var(--surface-white);
            max-width: 550px;
            width: 100%;
            border-radius: var(--radius-md);
            overflow: hidden;
            box-shadow: var(--shadow-lg);
            transform: translateY(20px);
            transition: var(--transition);
            border-top: 6px solid var(--accent-orange);
        }

        .modal-overlay.active .modal-card {
            transform: translateY(0);
        }

        .modal-header {
            padding: 1.25rem 1.5rem;
            background: #FFF5F5;
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-bottom: 1px solid var(--border-color);
        }

        .modal-header h3 {
            color: var(--accent-orange);
            display: flex;
            align-items: center;
            gap: 0.5rem;
            font-size: 1.15rem;
        }

        .modal-body {
            padding: 1.5rem;
            font-size: 0.95rem;
            color: var(--text-dark);
        }

        .modal-footer {
            padding: 1rem 1.5rem;
            background: var(--bg-light);
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-top: 1px solid var(--border-color);
        }

        /* Admin CMS Panel */
        .admin-panel {
            display: none;
            background: #1E293B;
            color: #F8FAFC;
            padding: 2rem 0;
            border-bottom: 4px solid var(--accent-gold);
        }

        .admin-panel.active {
            display: block;
        }

        .admin-grid {
            display: grid;
            grid-template-columns: 240px 1fr;
            gap: 2rem;
        }

        .admin-sidebar {
            background: #0F172A;
            padding: 1rem;
            border-radius: var(--radius-sm);
        }

        .admin-nav-item {
            padding: 0.75rem 1rem;
            display: block;
            color: #94A3B8;
            border-radius: 4px;
            margin-bottom: 0.4rem;
            cursor: pointer;
            font-size: 0.9rem;
        }

        .admin-nav-item.active, .admin-nav-item:hover {
            background: var(--primary-navy);
            color: var(--surface-white);
        }

        .admin-content {
            background: #0F172A;
            padding: 1.5rem;
            border-radius: var(--radius-sm);
        }

        .form-group {
            margin-bottom: 1.25rem;
        }

        .form-group label {
            display: block;
            font-size: 0.85rem;
            margin-bottom: 0.4rem;
            color: #CBD5E1;
        }

        .form-control {
            width: 100%;
            padding: 0.65rem 0.85rem;
            border-radius: 4px;
            border: 1px solid #334155;
            background: #1E293B;
            color: #FFF;
            font-size: 0.9rem;
        }

        .form-control:focus {
            outline: none;
            border-color: var(--secondary-teal);
        }

        /* Photo upload widget (used across every admin form) */
        .upload-field {
            border: 1px dashed #334155;
            border-radius: var(--radius-sm);
            padding: 0.85rem;
            background: #1E293B;
        }

        .upload-field input[type="file"] {
            width: 100%;
            font-size: 0.8rem;
            color: #CBD5E1;
        }

        .upload-preview {
            width: 80px;
            height: 80px;
            object-fit: cover;
            border-radius: 8px;
            margin-top: 0.6rem;
            border: 2px solid var(--secondary-teal);
            display: none;
        }

        .item-thumb {
            width: 46px;
            height: 46px;
            object-fit: cover;
            border-radius: 6px;
            margin-right: 0.6rem;
            border: 1px solid #334155;
            vertical-align: middle;
        }

        /* Tables */
        .table-responsive {
            width: 100%;
            overflow-x: auto;
        }

        .custom-table {
            width: 100%;
            border-collapse: collapse;
            text-align: left;
            font-size: 0.9rem;
        }

        .custom-table th, .custom-table td {
            padding: 0.85rem 1rem;
            border-bottom: 1px solid var(--border-color);
        }

        .custom-table th {
            background-color: var(--bg-light);
            color: var(--primary-navy);
            font-weight: 600;
        }

        /* Search Bar */
        .search-section {
            background: var(--primary-navy);
            padding: 1.25rem 0;
        }

        .search-box {
            display: flex;
            max-width: 600px;
            margin: 0 auto;
            position: relative;
        }

        .search-box input {
            width: 100%;
            padding: 0.85rem 1.25rem;
            border-radius: 50px;
            border: none;
            font-size: 0.95rem;
            outline: none;
        }

        .search-box button {
            position: absolute;
            right: 5px;
            top: 5px;
            bottom: 5px;
            border-radius: 50px;
            padding: 0 1.25rem;
        }

        /* Tab Buttons */
        .tab-buttons {
            display: flex;
            gap: 0.5rem;
            border-bottom: 2px solid var(--border-color);
            margin-bottom: 1.5rem;
            overflow-x: auto;
        }

        .tab-btn {
            padding: 0.75rem 1.25rem;
            background: none;
            border: none;
            font-weight: 600;
            color: var(--text-muted);
            cursor: pointer;
            border-bottom: 3px solid transparent;
            margin-bottom: -2px;
            white-space: nowrap;
        }

        .tab-btn.active {
            color: var(--primary-navy);
            border-bottom-color: var(--secondary-teal);
        }

        /* Footer */
        .footer {
            background: var(--primary-navy);
            color: var(--surface-white);
            padding-top: 4rem;
        }

        .footer-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 2.5rem;
            padding-bottom: 3rem;
            border-bottom: 1px solid rgba(255,255,255,0.1);
        }

        .footer-col h3 {
            color: var(--accent-gold);
            font-size: 1.1rem;
            margin-bottom: 1.25rem;
            position: relative;
        }

        .footer-col ul li {
            margin-bottom: 0.6rem;
        }

        .footer-col ul li a {
            color: rgba(255,255,255,0.75);
            font-size: 0.88rem;
            transition: var(--transition);
        }

        .footer-col ul li a:hover {
            color: var(--accent-gold);
            padding-left: 4px;
        }

        .footer-bottom {
            padding: 1.5rem 0;
            text-align: center;
            font-size: 0.85rem;
            color: rgba(255,255,255,0.6);
        }

        .page-view {
            display: none;
        }
        .page-view.active {
            display: block;
        }

        .editable-placeholder {
            color: var(--accent-orange);
            font-weight: 600;
            font-style: italic;
        }

        /* Responsive */
        @media (max-width: 992px) {
            .grid-4 { grid-template-columns: repeat(2, 1fr); }
            .grid-3 { grid-template-columns: repeat(2, 1fr); }
            .hero h1 { font-size: 2.25rem; }
            .admin-grid { grid-template-columns: 1fr; }
        }

        @media (max-width: 768px) {
            .top-bar-info { display: none; }
            .header-content { flex-direction: column; align-items: flex-start; gap: 1rem; }
            .mobile-toggle { display: block; position: absolute; right: 1.5rem; top: 1.5rem; }
            .nav-menu { display: none; flex-direction: column; width: 100%; }
            .nav-menu.show { display: flex; }
            .nav-link { border-bottom: 1px solid rgba(255,255,255,0.05); }
            .grid-2, .grid-3, .grid-4 { grid-template-columns: 1fr; }
            .hero { min-height: 60vh; }
            .hero h1 { font-size: 1.8rem; }
            .stats-section { margin-top: 2rem; }
            .modal-card { width: 95%; }
        }
    </style>
</head>
<body>

    <!-- TOP INFORMATION BAR -->
    <div class="top-bar">
        <div class="container top-bar-content">
            <div class="top-bar-info">
                <span><i class="fa-solid fa-phone"></i> <span id="top-bar-phone">[Editable Phone]</span></span>
                <span><i class="fa-solid fa-envelope"></i> <span id="top-bar-email">[Editable Email]</span></span>
                <span><i class="fa-solid fa-clock"></i> Mon - Sat: 09:00 AM - 04:00 PM</span>
            </div>
            <div class="top-bar-actions">
                <a href="#contact" onclick="navigateTo('contact')" class="btn btn-accent" style="padding: 0.25rem 0.75rem; font-size: 0.75rem;"><i class="fa-solid fa-paper-plane"></i> Contact School</a>
                <button id="admin-toggle-btn" onclick="openAdminAuth()" class="btn btn-primary" style="padding: 0.25rem 0.75rem; font-size: 0.75rem; background: var(--secondary-teal);"><i class="fa-solid fa-lock"></i> Admin Login</button>
            </div>
        </div>
    </div>

    <!-- MAIN HEADER -->
    <header class="main-header">
        <div class="container header-content">
            <button class="mobile-toggle" onclick="toggleMobileNav()"><i class="fa-solid fa-bars"></i></button>
            <div class="brand-container">
                <div class="school-logo" id="school-logo-holder">
                    <i class="fa-solid fa-graduation-cap"></i>
                </div>
                <div class="brand-text">
                    <h1>GOVT. GIRLS HIGHER SECONDARY SCHOOL HAGNIS</h1>
                    <div class="location"><i class="fa-solid fa-location-dot" style="color: var(--accent-orange);"></i> Hagnis, Chiktan, District Kargil, UT Ladakh, India - 194109</div>
                </div>
            </div>
            <div class="header-actions">
                <button onclick="showUrgentNoticeModal()" class="btn btn-accent"><i class="fa-solid fa-bell"></i> Latest Notice</button>
            </div>
        </div>
    </header>

    <!-- NAVIGATION MENU -->
    <nav class="nav-bar ladakh-border-top">
        <div class="container nav-container">
            <ul class="nav-menu" id="main-nav">
                <li class="nav-item"><a href="#home" class="nav-link active" onclick="navigateTo('home')">HOME</a></li>
                <li class="nav-item"><a href="#about" class="nav-link" onclick="navigateTo('about')">ABOUT US</a></li>
                <li class="nav-item"><a href="#info" class="nav-link" onclick="navigateTo('info')">SCHOOL PROFILE</a></li>
                <li class="nav-item"><a href="#academics" class="nav-link" onclick="navigateTo('academics')">ACADEMICS</a></li>
                <li class="nav-item"><a href="#faculty" class="nav-link" onclick="navigateTo('faculty')">FACULTY & STAFF</a></li>
                <li class="nav-item"><a href="#facilities" class="nav-link" onclick="navigateTo('facilities')">FACILITIES</a></li>
                <li class="nav-item"><a href="#events" class="nav-link" onclick="navigateTo('events')">EVENTS</a></li>
                <li class="nav-item"><a href="#gallery" class="nav-link" onclick="navigateTo('gallery')">GALLERY</a></li>
                <li class="nav-item"><a href="#notices" class="nav-link" onclick="navigateTo('notices')">NOTICES</a></li>
                <li class="nav-item"><a href="#downloads" class="nav-link" onclick="navigateTo('downloads')">DOCUMENTS</a></li>
                <li class="nav-item"><a href="#links" class="nav-link" onclick="navigateTo('links')">IMPORTANT LINKS</a></li>
                <li class="nav-item"><a href="#contact" class="nav-link" onclick="navigateTo('contact')">CONTACT US</a></li>
            </ul>
        </div>
    </nav>

    <!-- ANNOUNCEMENT TICKER -->
    <div class="ticker-bar">
        <div class="ticker-title"><i class="fa-solid fa-bullhorn"></i> Announcement</div>
        <div class="ticker-content" id="announcement-ticker">
            Welcome to the Official Web Portal of Government Girls Higher Secondary School Hagnis, Chiktan, Kargil, UT Ladakh (PIN: 194109).
        </div>
    </div>

    <!-- SEARCH BAR SECTION -->
    <div class="search-section">
        <div class="container">
            <div class="search-box">
                <input type="text" id="global-search-input" placeholder="Search notices, events, faculty, facilities, or school info..." onkeyup="handleGlobalSearch()">
                <button class="btn btn-accent"><i class="fa-solid fa-magnifying-glass"></i> Search</button>
            </div>
        </div>
    </div>

    <!-- ADMIN LOGIN MODAL -->
    <div class="modal-overlay" id="admin-login-modal">
        <div class="modal-card">
            <div class="modal-header">
                <h3><i class="fa-solid fa-user-shield"></i> Administrator Authentication</h3>
                <button onclick="closeAdminAuth()" style="background: none; border: none; font-size: 1.25rem; cursor: pointer; color: var(--text-muted);">&times;</button>
            </div>
            <div class="modal-body">
                <p style="margin-bottom: 1rem; font-size: 0.85rem; color: var(--text-muted);">Please enter administrative credentials to unlock website content management controls.</p>
                <div class="form-group">
                    <label style="color: var(--text-dark);">User ID</label>
                    <input type="text" id="login-userid" class="form-control" style="background:#FFF; color:#000; border:1px solid var(--border-color);" placeholder="Enter User ID" autocomplete="off">
                </div>
                <div class="form-group">
                    <label style="color: var(--text-dark);">Password</label>
                    <input type="password" id="login-password" class="form-control" style="background:#FFF; color:#000; border:1px solid var(--border-color);" placeholder="Enter Password" autocomplete="off">
                </div>
                <div id="login-error" style="color: #D32F2F; font-size: 0.85rem; display: none; margin-bottom: 0.5rem;">Invalid User ID or Password.</div>
            </div>
            <div class="modal-footer">
                <button onclick="closeAdminAuth()" class="btn btn-outline" style="padding: 0.4rem 1rem;">Cancel</button>
                <button onclick="processAdminLogin()" class="btn btn-primary" style="padding: 0.4rem 1rem;">Log In</button>
            </div>
        </div>
    </div>

    <!-- ADMIN PANEL / CMS DASHBOARD -->
    <div class="admin-panel" id="admin-panel">
        <div class="container">
            <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 1.5rem; border-bottom: 1px solid #334155; padding-bottom: 1rem;">
                <h2><i class="fa-solid fa-sliders"></i> School Content Management System</h2>
                <div style="display: flex; gap: 0.5rem;">
                    <button onclick="logoutAdmin()" class="btn btn-danger" style="padding: 0.3rem 0.8rem; font-size: 0.8rem;"><i class="fa-solid fa-right-from-bracket"></i> Logout</button>
                    <button onclick="toggleAdminPanelVisibility()" class="btn btn-accent" style="padding: 0.3rem 0.8rem; font-size: 0.8rem;">Hide Panel</button>
                </div>
            </div>
            <div class="admin-grid">
                <div class="admin-sidebar">
                    <div class="admin-nav-item active" onclick="switchAdminTab('general')"><i class="fa-solid fa-gear"></i> General Settings</div>
                    <div class="admin-nav-item" onclick="switchAdminTab('notice')"><i class="fa-solid fa-bullhorn"></i> Manage Notices</div>
                    <div class="admin-nav-item" onclick="switchAdminTab('faculty')"><i class="fa-solid fa-user-tie"></i> Manage Staff</div>
                    <div class="admin-nav-item" onclick="switchAdminTab('facility')"><i class="fa-solid fa-building"></i> Manage Facilities</div>
                    <div class="admin-nav-item" onclick="switchAdminTab('links')"><i class="fa-solid fa-link"></i> Manage Links</div>
                    <div class="admin-nav-item" onclick="switchAdminTab('gallery')"><i class="fa-solid fa-image"></i> Manage Gallery</div>
                    <div class="admin-nav-item" onclick="switchAdminTab('profile')"><i class="fa-solid fa-id-card"></i> School Profile</div>
                    <div class="admin-nav-item" onclick="switchAdminTab('events')"><i class="fa-solid fa-calendar-days"></i> Manage Events</div>
                    <div class="admin-nav-item" onclick="switchAdminTab('documents')"><i class="fa-solid fa-file-lines"></i> Manage Documents</div>
                </div>
                <div class="admin-content">
                    <!-- General Settings Form -->
                    <div id="admin-tab-general" class="admin-tab-pane">
                        <h3 style="margin-bottom: 1rem; color: var(--accent-gold);">General Site Settings</h3>
                        <div class="form-group">
                            <label>School Logo Photo</label>
                            <div class="upload-field">
                                <input type="file" accept="image/*" id="cfg-logo-file" onchange="handleLogoUpload(this)">
                                <img id="cfg-logo-preview" class="upload-preview" alt="Logo Preview">
                            </div>
                        </div>
                        <div class="form-group">
                            <label>School Phone Contact</label>
                            <input type="text" id="cfg-phone" class="form-control" placeholder="Enter Phone">
                        </div>
                        <div class="form-group">
                            <label>Official Email Address</label>
                            <input type="email" id="cfg-email" class="form-control" placeholder="Enter Email">
                        </div>
                        <div class="form-group">
                            <label>Announcement Ticker Text</label>
                            <input type="text" id="cfg-ticker" class="form-control" placeholder="Enter Ticker Message">
                        </div>
                        <div class="form-group">
                            <label>Head of Institution Name</label>
                            <input type="text" id="cfg-principal" class="form-control" placeholder="Enter Principal Name">
                        </div>
                        <div class="form-group">
                            <label>Principal Photo</label>
                            <div class="upload-field">
                                <input type="file" accept="image/*" id="cfg-principal-photo-file" onchange="handlePrincipalPhotoUpload(this)">
                                <img id="cfg-principal-photo-preview" class="upload-preview" alt="Principal Preview">
                            </div>
                        </div>
                        <div class="form-group">
                            <label>Principal Message</label>
                            <textarea id="cfg-principal-msg" class="form-control" rows="3" placeholder="Enter Principal Message"></textarea>
                        </div>
                        <button onclick="saveGeneralConfig()" class="btn btn-accent">Save Changes</button>
                    </div>

                    <!-- Manage Notices -->
                    <div id="admin-tab-notice" class="admin-tab-pane" style="display: none;">
                        <h3 style="margin-bottom: 1rem; color: var(--accent-gold);">Add New Notice</h3>
                        <div class="form-group">
                            <label>Notice Title</label>
                            <input type="text" id="adm-notice-title" class="form-control" placeholder="Enter title">
                        </div>
                        <div class="form-group">
                            <label>Category</label>
                            <select id="adm-notice-cat" class="form-control">
                                <option value="urgent">Urgent</option>
                                <option value="academic">Academic</option>
                                <option value="general">General</option>
                            </select>
                        </div>
                        <div class="form-group">
                            <label>Details</label>
                            <textarea id="adm-notice-body" class="form-control" rows="3" placeholder="Enter notice details"></textarea>
                        </div>
                        <div class="form-group">
                            <label>Attach Notice Photo (optional)</label>
                            <div class="upload-field">
                                <input type="file" accept="image/*" id="adm-notice-photo-file" onchange="handleNoticePhotoSelect(this)">
                                <img id="adm-notice-photo-preview" class="upload-preview" alt="Notice Photo Preview">
                            </div>
                        </div>
                        <button onclick="addNoticeFromAdmin()" class="btn btn-accent">Publish Notice</button>

                        <h3 style="margin: 1.75rem 0 1rem; color: var(--accent-gold);">Existing Notices</h3>
                        <div id="adm-notice-manage-list"></div>
                    </div>

                    <!-- Manage Faculty -->
                    <div id="admin-tab-faculty" class="admin-tab-pane" style="display: none;">
                        <h3 style="margin-bottom: 1rem; color: var(--accent-gold);">Add Faculty / Staff Member</h3>
                        <div class="form-group">
                            <label>Staff Photo</label>
                            <div class="upload-field">
                                <input type="file" accept="image/*" id="adm-staff-photo-file" onchange="handleStaffPhotoSelect(this)">
                                <img id="adm-staff-photo-preview" class="upload-preview" alt="Staff Photo Preview">
                            </div>
                        </div>
                        <div class="form-group">
                            <label>Full Name</label>
                            <input type="text" id="adm-staff-name" class="form-control" placeholder="Name">
                        </div>
                        <div class="form-group">
                            <label>Designation</label>
                            <input type="text" id="adm-staff-role" class="form-control" placeholder="e.g., Lecturer Physics">
                        </div>
                        <div class="form-group">
                            <label>Qualification / Subject</label>
                            <input type="text" id="adm-staff-qual" class="form-control" placeholder="e.g., M.Sc, B.Ed">
                        </div>
                        <button onclick="addStaffFromAdmin()" class="btn btn-accent">Add Staff Member</button>

                        <h3 style="margin: 1.75rem 0 1rem; color: var(--accent-gold);">Existing Staff</h3>
                        <div id="adm-staff-manage-list"></div>
                    </div>

                    <!-- Manage Facilities -->
                    <div id="admin-tab-facility" class="admin-tab-pane" style="display: none;">
                        <h3 style="margin-bottom: 1rem; color: var(--accent-gold);">Add Facility</h3>
                        <div class="form-group">
                            <label>Facility Photo</label>
                            <div class="upload-field">
                                <input type="file" accept="image/*" id="adm-fac-photo-file" onchange="handleFacilityPhotoSelect(this)">
                                <img id="adm-fac-photo-preview" class="upload-preview" alt="Facility Photo Preview">
                            </div>
                        </div>
                        <div class="form-group">
                            <label>Facility Title</label>
                            <input type="text" id="adm-fac-title" class="form-control" placeholder="Facility Name">
                        </div>
                        <div class="form-group">
                            <label>Description</label>
                            <textarea id="adm-fac-desc" class="form-control" rows="2" placeholder="Details"></textarea>
                        </div>
                        <button onclick="addFacilityFromAdmin()" class="btn btn-accent">Add Facility</button>

                        <h3 style="margin: 1.75rem 0 1rem; color: var(--accent-gold);">Existing Facilities</h3>
                        <div id="adm-facility-manage-list"></div>
                    </div>

                    <!-- Manage Links -->
                    <div id="admin-tab-links" class="admin-tab-pane" style="display: none;">
                        <h3 style="margin-bottom: 1rem; color: var(--accent-gold);">Add Important Link</h3>
                        <div class="form-group">
                            <label>Link Icon / Photo (optional)</label>
                            <div class="upload-field">
                                <input type="file" accept="image/*" id="adm-link-photo-file" onchange="handleLinkPhotoSelect(this)">
                                <img id="adm-link-photo-preview" class="upload-preview" alt="Link Icon Preview">
                            </div>
                        </div>
                        <div class="form-group">
                            <label>Link Label Title</label>
                            <input type="text" id="adm-link-title" class="form-control" placeholder="e.g., UT Ladakh Official Portal">
                        </div>
                        <div class="form-group">
                            <label>URL</label>
                            <input type="url" id="adm-link-url" class="form-control" placeholder="https://...">
                        </div>
                        <button onclick="addLinkFromAdmin()" class="btn btn-accent">Save Link</button>

                        <h3 style="margin: 1.75rem 0 1rem; color: var(--accent-gold);">Existing Links</h3>
                        <div id="adm-link-manage-list"></div>
                    </div>

                    <!-- Manage Gallery -->
                    <div id="admin-tab-gallery" class="admin-tab-pane" style="display: none;">
                        <h3 style="margin-bottom: 1rem; color: var(--accent-gold);">Add Photo to Gallery</h3>
                        <div class="form-group">
                            <label>Upload Photo From Device</label>
                            <div class="upload-field">
                                <input type="file" accept="image/*" id="adm-gal-photo-file" onchange="handleGalleryPhotoSelect(this)">
                                <img id="adm-gal-photo-preview" class="upload-preview" alt="Gallery Photo Preview">
                            </div>
                        </div>
                        <div class="form-group">
                            <label>Image Caption Title</label>
                            <input type="text" id="adm-gal-title" class="form-control" placeholder="Title">
                        </div>
                        <div class="form-group">
                            <label>Or Paste Image URL (optional, used if no photo uploaded)</label>
                            <input type="url" id="adm-gal-url" class="form-control" placeholder="https://images.unsplash.com/...">
                        </div>
                        <button onclick="addGalleryFromAdmin()" class="btn btn-accent">Add Photo</button>

                        <h3 style="margin: 1.75rem 0 1rem; color: var(--accent-gold);">Existing Gallery Photos</h3>
                        <div id="adm-gallery-manage-list"></div>
                    </div>

                    <!-- Manage School Profile -->
                    <div id="admin-tab-profile" class="admin-tab-pane" style="display: none;">
                        <h3 style="margin-bottom: 1rem; color: var(--accent-gold);">School Profile & Master Data</h3>
                        <p style="color: #94A3B8; font-size: 0.85rem; margin-bottom: 1rem;">Edit any field value directly. Add new rows or remove rows that aren't needed — changes reflect instantly on the "School Profile" page.</p>

                        <div class="tab-buttons">
                            <button class="tab-btn active" onclick="switchAdminProfileSubtab(this, 'basic')">Basic Information</button>
                            <button class="tab-btn" onclick="switchAdminProfileSubtab(this, 'geo')">Geographical Data</button>
                            <button class="tab-btn" onclick="switchAdminProfileSubtab(this, 'infra')">Infrastructure Profile</button>
                        </div>

                        <div id="admin-profile-basic" class="admin-profile-subtab">
                            <div id="adm-profile-basic-list" style="margin-bottom: 1rem;"></div>
                            <div class="form-group">
                                <label>New Field Label</label>
                                <input type="text" id="adm-profile-basic-label" class="form-control" placeholder="e.g., Board Affiliation">
                            </div>
                            <div class="form-group">
                                <label>Value</label>
                                <input type="text" id="adm-profile-basic-value" class="form-control" placeholder="e.g., UT Ladakh Board">
                            </div>
                            <button onclick="addProfileField('basic')" class="btn btn-accent"><i class="fa-solid fa-plus"></i> Add Field</button>
                        </div>

                        <div id="admin-profile-geo" class="admin-profile-subtab" style="display: none;">
                            <div id="adm-profile-geo-list" style="margin-bottom: 1rem;"></div>
                            <div class="form-group">
                                <label>New Field Label</label>
                                <input type="text" id="adm-profile-geo-label" class="form-control" placeholder="e.g., Terrain Type">
                            </div>
                            <div class="form-group">
                                <label>Value</label>
                                <input type="text" id="adm-profile-geo-value" class="form-control" placeholder="e.g., Mountainous">
                            </div>
                            <button onclick="addProfileField('geo')" class="btn btn-accent"><i class="fa-solid fa-plus"></i> Add Field</button>
                        </div>

                        <div id="admin-profile-infra" class="admin-profile-subtab" style="display: none;">
                            <div id="adm-profile-infra-list" style="margin-bottom: 1rem;"></div>
                            <div class="form-group">
                                <label>New Field Label</label>
                                <input type="text" id="adm-profile-infra-label" class="form-control" placeholder="e.g., Playground Area">
                            </div>
                            <div class="form-group">
                                <label>Value</label>
                                <input type="text" id="adm-profile-infra-value" class="form-control" placeholder="e.g., 0.5 Acres">
                            </div>
                            <button onclick="addProfileField('infra')" class="btn btn-accent"><i class="fa-solid fa-plus"></i> Add Field</button>
                        </div>
                    </div>

                    <!-- Manage Events -->
                    <div id="admin-tab-events" class="admin-tab-pane" style="display: none;">
                        <h3 style="margin-bottom: 1rem; color: var(--accent-gold);">Add School Event</h3>
                        <div class="form-group">
                            <label>Event Title</label>
                            <input type="text" id="adm-event-title" class="form-control" placeholder="e.g., Annual Sports Meet">
                        </div>
                        <div class="form-group">
                            <label>Category Tag</label>
                            <select id="adm-event-tag" class="form-control">
                                <option value="CULTURAL & NATIONAL">Cultural & National</option>
                                <option value="ACADEMIC & SCIENCE">Academic & Science</option>
                                <option value="SPORTS & ATHLETICS">Sports & Athletics</option>
                                <option value="GENERAL">General</option>
                            </select>
                        </div>
                        <div class="form-group">
                            <label>Description</label>
                            <textarea id="adm-event-desc" class="form-control" rows="3" placeholder="Details of the event"></textarea>
                        </div>
                        <button onclick="addEventFromAdmin()" class="btn btn-accent">Publish Event</button>

                        <h3 style="margin: 1.75rem 0 1rem; color: var(--accent-gold);">Existing Events</h3>
                        <div id="adm-event-manage-list"></div>
                    </div>

                    <!-- Manage Documents -->
                    <div id="admin-tab-documents" class="admin-tab-pane" style="display: none;">
                        <h3 style="margin-bottom: 1rem; color: var(--accent-gold);">Add Downloadable Document</h3>
                        <div class="form-group">
                            <label>Document Name</label>
                            <input type="text" id="adm-doc-name" class="form-control" placeholder="e.g., Scholarship Application Form">
                        </div>
                        <div class="form-group">
                            <label>Category</label>
                            <input type="text" id="adm-doc-category" class="form-control" placeholder="e.g., Admissions">
                        </div>
                        <div class="form-group">
                            <label>Format</label>
                            <select id="adm-doc-format" class="form-control">
                                <option value="PDF">PDF</option>
                                <option value="DOC">DOC</option>
                                <option value="XLS">XLS</option>
                                <option value="IMAGE">Image</option>
                            </select>
                        </div>
                        <div class="form-group">
                            <label>Document Link (optional)</label>
                            <input type="url" id="adm-doc-url" class="form-control" placeholder="https://... (leave blank if not hosted online)">
                        </div>
                        <button onclick="addDocumentFromAdmin()" class="btn btn-accent">Add Document</button>

                        <h3 style="margin: 1.75rem 0 1rem; color: var(--accent-gold);">Existing Documents</h3>
                        <div id="adm-document-manage-list"></div>
                    </div>

                </div>
            </div>
        </div>
    </div>

    <!-- MAIN PAGE CONTENT CONTAINER -->
    <main>

        <!-- PAGE 1: HOME PAGE -->
        <div id="page-home" class="page-view active">
            <!-- Hero Section -->
            <section class="hero">
                <div class="container">
                    <div class="hero-content">
                        <span class="hero-badge"><i class="fa-solid fa-award"></i> Government Girls Higher Secondary School Hagnis</span>
                        <h1>Empowering Girls Through Education, Knowledge, Character & Opportunity</h1>
                        <p>Fostering academic growth, leadership, and holistic development in the scenic village of Hagnis, Chiktan, District Kargil, UT Ladakh (194109).</p>
                        <div class="hero-buttons">
                            <button onclick="navigateTo('about')" class="btn btn-accent"><i class="fa-solid fa-compass"></i> Explore Our School</button>
                            <button onclick="navigateTo('notices')" class="btn btn-primary" style="background: rgba(255,255,255,0.2); border: 1px solid #FFF;"><i class="fa-solid fa-bullhorn"></i> View Notices</button>
                        </div>
                    </div>
                </div>
            </section>

            <!-- Quick Stats Section -->
            <section class="stats-section">
                <div class="container">
                    <div class="stats-grid">
                        <div class="stat-card">
                            <div class="stat-icon"><i class="fa-solid fa-calendar-check"></i></div>
                            <div class="stat-number" id="stat-est">[Year]</div>
                            <div class="stat-label">Year Established</div>
                        </div>
                        <div class="stat-card">
                            <div class="stat-icon"><i class="fa-solid fa-user-graduate"></i></div>
                            <div class="stat-number" id="stat-students">[Count]</div>
                            <div class="stat-label">Enrolled Students</div>
                        </div>
                        <div class="stat-card">
                            <div class="stat-icon"><i class="fa-solid fa-chalkboard-user"></i></div>
                            <div class="stat-number" id="stat-faculty">[Count]</div>
                            <div class="stat-label">Teaching Staff</div>
                        </div>
                        <div class="stat-card">
                            <div class="stat-icon"><i class="fa-solid fa-school"></i></div>
                            <div class="stat-number">Classes 9th - 12th</div>
                            <div class="stat-label">Academic Level</div>
                        </div>
                    </div>
                </div>
            </section>

            <!-- Welcome & Principal Message -->
            <section class="section-padding">
                <div class="container">
                    <div class="grid-2">
                        <div class="card card-body">
                            <h2 style="color: var(--primary-navy); margin-bottom: 1rem;"><i class="fa-solid fa-landmark"></i> Welcome to GGHSS Hagnis</h2>
                            <p style="margin-bottom: 1rem; color: var(--text-dark);">
                                Government Girls Higher Secondary School Hagnis stands as a premier educational institution dedicated to female empowerment in the Chiktan region of Kargil District, UT Ladakh.
                            </p>
                            <p style="color: var(--text-muted); font-size: 0.95rem;">
                                Our institution provides structured academic learning, modern educational tools, and holistic co-curricular opportunities in a safe, inspiring Himalayan learning environment.
                            </p>
                        </div>
                        <div class="card card-body" style="border-left: 4px solid var(--accent-gold);">
                            <div style="display: flex; gap: 1rem; align-items: center; margin-bottom: 1rem;">
                                <div id="principal-photo-holder" style="width: 70px; height: 70px; border-radius: 50%; background: var(--border-color); display: flex; align-items: center; justify-content: center; font-size: 1.8rem; color: var(--primary-navy); overflow: hidden; flex-shrink: 0;">
                                    <i class="fa-solid fa-user-tie"></i>
                                </div>
                                <div>
                                    <h3 style="font-size: 1.1rem; color: var(--primary-navy);" id="principal-name">[Principal Name]</h3>
                                    <span style="font-size: 0.85rem; color: var(--secondary-teal); font-weight: 600;">Head of Institution</span>
                                </div>
                            </div>
                            <blockquote style="font-style: italic; color: var(--text-muted); font-size: 0.95rem;" id="principal-message">
                                "[Principal / Head of Institution Message Placeholder: Log in to the Admin Dashboard to update the official message.]"
                            </blockquote>
                        </div>
                    </div>
                </div>
            </section>

            <!-- Latest Notices & Events Highlights -->
            <section class="section-padding" style="background: #F1F5F9;">
                <div class="container">
                    <div class="grid-2">
                        <div>
                            <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 1.5rem;">
                                <h3 style="color: var(--primary-navy);"><i class="fa-solid fa-bell"></i> Latest Official Notices</h3>
                                <a href="#notices" onclick="navigateTo('notices')" style="color: var(--secondary-teal); font-weight: 600; font-size: 0.9rem;">View All →</a>
                            </div>
                            <div id="home-notice-list">
                                <!-- Dynamic Notice Render -->
                            </div>
                        </div>
                        <div>
                            <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 1.5rem;">
                                <h3 style="color: var(--primary-navy);"><i class="fa-solid fa-calendar-days"></i> Upcoming Events</h3>
                                <a href="#events" onclick="navigateTo('events')" style="color: var(--secondary-teal); font-weight: 600; font-size: 0.9rem;">View All →</a>
                            </div>
                            <div class="card card-body" style="margin-bottom: 1rem;">
                                <span style="font-size: 0.75rem; font-weight: 700; color: var(--accent-orange); text-transform: uppercase;">Academic & Cultural</span>
                                <h4 style="margin: 0.3rem 0; color: var(--primary-navy);">Annual School Sports & Cultural Meet</h4>
                                <p style="font-size: 0.85rem; color: var(--text-muted);"><i class="fa-solid fa-clock"></i> Schedule announced via circular.</p>
                            </div>
                            <div class="card card-body">
                                <span style="font-size: 0.75rem; font-weight: 700; color: var(--secondary-teal); text-transform: uppercase;">Community Drive</span>
                                <h4 style="margin: 0.3rem 0; color: var(--primary-navy);">Himalayan Ecology & Environmental Drive</h4>
                                <p style="font-size: 0.85rem; color: var(--text-muted);"><i class="fa-solid fa-clock"></i> Student Eco-Club Initiative.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
        </div>

        <!-- PAGE 2: ABOUT US -->
        <div id="page-about" class="page-view">
            <section class="section-padding">
                <div class="container">
                    <div class="section-header">
                        <h2>About Our Institution</h2>
                        <p>Empowering female students through academic rigor, character building, and community participation in Hagnis, Chiktan, Kargil.</p>
                    </div>

                    <div class="grid-3" style="margin-bottom: 3rem;">
                        <div class="card card-body" style="border-top: 4px solid var(--primary-navy);">
                            <div style="font-size: 2rem; color: var(--primary-navy); margin-bottom: 1rem;"><i class="fa-solid fa-eye"></i></div>
                            <h3 style="color: var(--primary-navy); margin-bottom: 0.75rem;">Our Vision</h3>
                            <p style="font-size: 0.9rem; color: var(--text-muted);">To serve as a center of educational opportunity and holistic empowerment for girls in high-altitude rural regions, fostering intellectual curiosity and cultural dignity.</p>
                        </div>
                        <div class="card card-body" style="border-top: 4px solid var(--secondary-teal);">
                            <div style="font-size: 2rem; color: var(--secondary-teal); margin-bottom: 1rem;"><i class="fa-solid fa-bullseye"></i></div>
                            <h3 style="color: var(--primary-navy); margin-bottom: 0.75rem;">Our Mission</h3>
                            <p style="font-size: 0.9rem; color: var(--text-muted);">Deliver standard secondary and higher secondary education through modern pedagogy, digital tools, science learning, and leadership opportunities.</p>
                        </div>
                        <div class="card card-body" style="border-top: 4px solid var(--accent-gold);">
                            <div style="font-size: 2rem; color: var(--accent-gold); margin-bottom: 1rem;"><i class="fa-solid fa-heart"></i></div>
                            <h3 style="color: var(--primary-navy); margin-bottom: 0.75rem;">Core Values</h3>
                            <p style="font-size: 0.9rem; color: var(--text-muted);">Integrity, Inclusivity, Respect for Ladakhi Heritage, Environmental Stewardship, and Commitment to Female Literacy.</p>
                        </div>
                    </div>

                    <div class="card card-body">
                        <h3 style="color: var(--primary-navy); margin-bottom: 1rem;">Institutional Overview & Community Impact</h3>
                        <p style="margin-bottom: 1rem; color: var(--text-dark);">
                            Government Girls Higher Secondary School Hagnis plays a vital role in catering to secondary and senior secondary educational requirements across Hagnis and neighboring villages in Chiktan block, Kargil District.
                        </p>
                        <p style="color: var(--text-muted);">
                            By combining academic instruction with co-curricular activities, sports, environmental awareness, and cultural celebrations, the school prepares young women for higher studies and active leadership.
                        </p>
                    </div>
                </div>
            </section>
        </div>

        <!-- PAGE 3: SCHOOL PROFILE / MASTER DATA -->
        <div id="page-info" class="page-view">
            <section class="section-padding">
                <div class="container">
                    <div class="section-header">
                        <h2>Complete School Profile & Master Data</h2>
                        <p>Official Institutional Record, Geographical Coordinates, and Infrastructure Profile</p>
                    </div>

                    <div class="tab-buttons">
                        <button class="tab-btn active" onclick="switchProfileTab(this, 'prof-basic')">Basic Information</button>
                        <button class="tab-btn" onclick="switchProfileTab(this, 'prof-geo')">Geographical Data</button>
                        <button class="tab-btn" onclick="switchProfileTab(this, 'prof-infra')">Infrastructure Profile</button>
                    </div>

                    <div id="prof-basic" class="profile-tab-content">
                        <div class="card card-body">
                            <div class="table-responsive">
                                <table class="custom-table">
                                    <tbody id="prof-basic-body"></tbody>
                                </table>
                            </div>
                        </div>
                    </div>

                    <div id="prof-geo" class="profile-tab-content" style="display: none;">
                        <div class="card card-body">
                            <div class="table-responsive">
                                <table class="custom-table">
                                    <tbody id="prof-geo-body"></tbody>
                                </table>
                            </div>
                        </div>
                    </div>

                    <div id="prof-infra" class="profile-tab-content" style="display: none;">
                        <div class="card card-body">
                            <div class="table-responsive">
                                <table class="custom-table">
                                    <tbody id="prof-infra-body"></tbody>
                                </table>
                            </div>
                        </div>
                    </div>

                </div>
            </section>
        </div>

        <!-- PAGE 4: ACADEMICS -->
        <div id="page-academics" class="page-view">
            <section class="section-padding">
                <div class="container">
                    <div class="section-header">
                        <h2>Academic Structure & Offerings</h2>
                        <p>Providing secondary and higher secondary education aligned with official board curricula.</p>
                    </div>

                    <div class="grid-4" style="margin-bottom: 3rem;">
                        <div class="card card-body text-center">
                            <h3 style="color: var(--primary-navy); margin-bottom: 0.5rem;">Class 9th</h3>
                            <p style="font-size: 0.85rem; color: var(--text-muted);">Secondary Level Foundation</p>
                        </div>
                        <div class="card card-body text-center">
                            <h3 style="color: var(--primary-navy); margin-bottom: 0.5rem;">Class 10th</h3>
                            <p style="font-size: 0.85rem; color: var(--text-muted);">Board Examination Preparation</p>
                        </div>
                        <div class="card card-body text-center">
                            <h3 style="color: var(--primary-navy); margin-bottom: 0.5rem;">Class 11th</h3>
                            <p style="font-size: 0.85rem; color: var(--text-muted);">Higher Secondary Streams</p>
                        </div>
                        <div class="card card-body text-center">
                            <h3 style="color: var(--primary-navy); margin-bottom: 0.5rem;">Class 12th</h3>
                            <p style="font-size: 0.85rem; color: var(--text-muted);">Senior Secondary Certification</p>
                        </div>
                    </div>

                    <div class="card card-body">
                        <h3 style="color: var(--primary-navy); margin-bottom: 1rem;">Curriculum & Subject Domains</h3>
                        <p style="color: var(--text-muted); margin-bottom: 1rem;">
                            The academic framework strictly adheres to the standards established by the Directorate of School Education, UT Ladakh.
                        </p>
                        <div class="grid-2">
                            <ul>
                                <li><i class="fa-solid fa-check" style="color: var(--secondary-teal);"></i> Physics, Chemistry, Biology</li>
                                <li><i class="fa-solid fa-check" style="color: var(--secondary-teal);"></i> Mathematics & Computer Applications</li>
                                <li><i class="fa-solid fa-check" style="color: var(--secondary-teal);"></i> History, Political Science, Geography</li>
                            </ul>
                            <ul>
                                <li><i class="fa-solid fa-check" style="color: var(--secondary-teal);"></i> English Literature & Functional English</li>
                                <li><i class="fa-solid fa-check" style="color: var(--secondary-teal);"></i> Urdu, Hindi, Bhoti</li>
                                <li><i class="fa-solid fa-check" style="color: var(--secondary-teal);"></i> Environmental Science & Health Studies</li>
                            </ul>
                        </div>
                    </div>
                </div>
            </section>
        </div>

        <!-- PAGE 5: FACULTY & STAFF -->
        <div id="page-faculty" class="page-view">
            <section class="section-padding">
                <div class="container">
                    <div class="section-header">
                        <h2>Faculty & Administrative Staff</h2>
                        <p>Dedicated teachers and support staff serving GGHSS Hagnis.</p>
                    </div>

                    <div class="grid-3" id="faculty-grid">
                        <!-- Dynamic Faculty Render -->
                    </div>
                </div>
            </section>
        </div>

        <!-- PAGE 6: FACILITIES -->
        <div id="page-facilities" class="page-view">
            <section class="section-padding">
                <div class="container">
                    <div class="section-header">
                        <h2>Campus Facilities & Infrastructure</h2>
                        <p>Facilities supporting academic learning, practical experiments, and student well-being.</p>
                    </div>

                    <div class="grid-3" id="facilities-grid">
                        <!-- Dynamic Facilities Render -->
                    </div>
                </div>
            </section>
        </div>

        <!-- PAGE 7: EVENTS -->
        <div id="page-events" class="page-view">
            <section class="section-padding">
                <div class="container">
                    <div class="section-header">
                        <h2>School Events & Co-Curricular Calendar</h2>
                        <p>Glimpses of academic competitions, national days, and cultural celebrations.</p>
                    </div>

                    <div class="grid-2" id="events-grid">
                        <!-- Dynamic Events Render -->
                    </div>
                </div>
            </section>
        </div>

        <!-- PAGE 8: GALLERY -->
        <div id="page-gallery" class="page-view">
            <section class="section-padding">
                <div class="container">
                    <div class="section-header">
                        <h2>Photo Gallery</h2>
                        <p>Visual highlights of school activities, campus grounds, and events.</p>
                    </div>

                    <div class="gallery-grid" id="gallery-grid-container">
                        <!-- Dynamic Gallery Render -->
                    </div>
                </div>
            </section>
        </div>

        <!-- PAGE 9: NOTICES -->
        <div id="page-notices" class="page-view">
            <section class="section-padding">
                <div class="container">
                    <div class="section-header">
                        <h2>Official Notice Board</h2>
                        <p>Digital repository for school orders, examination notices, and departmental circulars.</p>
                    </div>

                    <div class="card" id="full-notice-list">
                        <!-- Dynamic Notice Render -->
                    </div>
                </div>
            </section>
        </div>

        <!-- PAGE 10: DOWNLOADS / DOCUMENTS -->
        <div id="page-downloads" class="page-view">
            <section class="section-padding">
                <div class="container">
                    <div class="section-header">
                        <h2>Document Download Repository</h2>
                        <p>Official forms, syllabus documents, and downloadable school notices.</p>
                    </div>

                    <div class="card card-body">
                        <div class="table-responsive">
                            <table class="custom-table">
                                <thead>
                                    <tr>
                                        <th>Document Name</th>
                                        <th>Category</th>
                                        <th>Format</th>
                                        <th>Action</th>
                                    </tr>
                                </thead>
                                <tbody id="downloads-body">
                                    <!-- Dynamic Documents Render -->
                                </tbody>
                            </table>
                        </div>
                    </div>
                </div>
            </section>
        </div>

        <!-- PAGE 11: IMPORTANT LINKS -->
        <div id="page-links" class="page-view">
            <section class="section-padding">
                <div class="container">
                    <div class="section-header">
                        <h2>Important Government & Educational Portals</h2>
                        <p>Direct web links to official departments, education portals, and district sites.</p>
                    </div>

                    <div class="grid-3" id="links-grid">
                        <!-- Dynamic Links Render -->
                    </div>
                </div>
            </section>
        </div>

        <!-- PAGE 12: CONTACT US -->
        <div id="page-contact" class="page-view">
            <section class="section-padding">
                <div class="container">
                    <div class="section-header">
                        <h2>Contact School Administration</h2>
                        <p>Reach out for official inquiries, admissions assistance, or public information.</p>
                    </div>

                    <div class="grid-2">
                        <div class="card card-body">
                            <h3 style="color: var(--primary-navy); margin-bottom: 1.25rem;">Contact Information</h3>
                            <ul style="display: flex; flex-direction: column; gap: 1rem;">
                                <li>
                                    <strong><i class="fa-solid fa-location-dot" style="color: var(--accent-orange);"></i> Address:</strong><br>
                                    Government Girls Higher Secondary School Hagnis<br>
                                    Hagnis, Chiktan Block, District Kargil,<br>
                                    UT Ladakh, India - 194109
                                </li>
                                <li>
                                    <strong><i class="fa-solid fa-phone" style="color: var(--secondary-teal);"></i> Phone:</strong><br>
                                    <span id="contact-info-phone">[Editable Phone Field]</span>
                                </li>
                                <li>
                                    <strong><i class="fa-solid fa-envelope" style="color: var(--primary-navy);"></i> Email:</strong><br>
                                    <span id="contact-info-email">[Editable Email Field]</span>
                                </li>
                                <li>
                                    <strong><i class="fa-solid fa-clock" style="color: var(--accent-gold);"></i> Office Hours:</strong><br>
                                    Monday to Saturday: 09:00 AM to 04:00 PM
                                </li>
                            </ul>
                        </div>

                        <div class="card card-body">
                            <h3 style="color: var(--primary-navy); margin-bottom: 1.25rem;">Submit Online Message</h3>
                            <form onsubmit="handleContactSubmit(event)">
                                <div class="form-group">
                                    <label style="color: var(--text-dark);">Your Full Name</label>
                                    <input type="text" class="form-control" style="background: #FFF; color: #000; border: 1px solid var(--border-color);" required placeholder="Full Name">
                                </div>
                                <div class="form-group">
                                    <label style="color: var(--text-dark);">Email / Phone Number</label>
                                    <input type="text" class="form-control" style="background: #FFF; color: #000; border: 1px solid var(--border-color);" required placeholder="Contact Number or Email">
                                </div>
                                <div class="form-group">
                                    <label style="color: var(--text-dark);">Subject</label>
                                    <input type="text" class="form-control" style="background: #FFF; color: #000; border: 1px solid var(--border-color);" required placeholder="Inquiry Subject">
                                </div>
                                <div class="form-group">
                                    <label style="color: var(--text-dark);">Message</label>
                                    <textarea class="form-control" style="background: #FFF; color: #000; border: 1px solid var(--border-color);" rows="3" required placeholder="Write your message here..."></textarea>
                                </div>
                                <button type="submit" class="btn btn-primary" style="width: 100%;">Send Message</button>
                            </form>
                        </div>
                    </div>
                </div>
            </section>
        </div>

    </main>

    <!-- FOOTER -->
    <footer class="footer ladakh-border-top">
        <div class="container">
            <div class="footer-grid">
                <div class="footer-col">
                    <h3>GGHSS Hagnis</h3>
                    <p style="font-size: 0.85rem; color: rgba(255,255,255,0.7); margin-bottom: 1rem;">
                        Government Girls Higher Secondary School Hagnis, Chiktan, District Kargil, UT Ladakh (PIN: 194109).
                    </p>
                    <span style="font-size: 0.8rem; color: var(--accent-gold);">UT Ladakh, India</span>
                </div>
                <div class="footer-col">
                    <h3>Quick Navigation</h3>
                    <ul>
                        <li><a href="#about" onclick="navigateTo('about')">About Us</a></li>
                        <li><a href="#info" onclick="navigateTo('info')">School Profile</a></li>
                        <li><a href="#academics" onclick="navigateTo('academics')">Academic Program</a></li>
                        <li><a href="#notices" onclick="navigateTo('notices')">Notice Board</a></li>
                    </ul>
                </div>
                <div class="footer-col">
                    <h3>Key Portals</h3>
                    <ul>
                        <li><a href="#facilities" onclick="navigateTo('facilities')">Facilities</a></li>
                        <li><a href="#downloads" onclick="navigateTo('downloads')">Document Center</a></li>
                        <li><a href="#links" onclick="navigateTo('links')">Important Links</a></li>
                        <li><a href="#contact" onclick="navigateTo('contact')">Contact Us</a></li>
                    </ul>
                </div>
                <div class="footer-col">
                    <h3>Location Details</h3>
                    <p style="font-size: 0.85rem; color: rgba(255,255,255,0.7);">
                        Village Hagnis, Chiktan Block,<br>
                        District Kargil,<br>
                        UT Ladakh - 194109
                    </p>
                </div>
            </div>
            <div class="footer-bottom">
                <p>&copy; Government Girls Higher Secondary School Hagnis, Kargil, UT Ladakh - 194109. All Rights Reserved.</p>
            </div>
        </div>
    </footer>

    <!-- URGENT NOTICE POPUP MODAL -->
    <div class="modal-overlay" id="urgent-modal">
        <div class="modal-card">
            <div class="modal-header">
                <h3><i class="fa-solid fa-triangle-exclamation"></i> Official Urgent Notice</h3>
                <button onclick="closeUrgentNoticeModal()" style="background: none; border: none; font-size: 1.25rem; cursor: pointer; color: var(--text-muted);">&times;</button>
            </div>
            <div class="modal-body">
                <h4 style="color: var(--primary-navy); margin-bottom: 0.5rem;" id="modal-notice-title">Academic Session Circular</h4>
                <p style="color: var(--text-muted); font-size: 0.9rem;" id="modal-notice-desc">
                    Official updates, circulars, and admissions notifications are regularly updated on this portal.
                </p>
            </div>
            <div class="modal-footer">
                <label style="font-size: 0.8rem; color: var(--text-muted); cursor: pointer;">
                    <input type="checkbox" id="chk-dont-show"> Do not show again
                </label>
                <button onclick="closeUrgentNoticeModal()" class="btn btn-primary" style="padding: 0.4rem 1rem; font-size: 0.85rem;">Close Notice</button>
            </div>
        </div>
    </div>

    <!-- SCRIPT ENGINE & PERSISTENT STATE -->
    <script>
        // DEFAULT DATA STORE
        const DEFAULT_STATE = {
            isAdminLoggedIn: false,
            config: {
                phone: "[Editable Phone]",
                email: "[Editable Email]",
                ticker: "Welcome to Government Girls Higher Secondary School Hagnis, Chiktan, Kargil, UT Ladakh - 194109.",
                est: "[Year]",
                students: "[Count]",
                faculty: "[Count]",
                principalName: "[Head of Institution]",
                principalMsg: "[Principal / Head of Institution Message Placeholder: Log in to the Admin Dashboard to update the official message.]",
                logoUrl: "",
                principalPhotoUrl: ""
            },
            notices: [
                { id: 1, title: "Commencement of Academic Classes", date: "15", month: "MAY", category: "academic", body: "Regular classes for 9th to 12th standards will proceed according to the departmental timetable.", imageUrl: "" },
                { id: 2, title: "Free Textbook & Uniform Distribution Drive", date: "02", month: "JUN", category: "urgent", body: "Enrolled female students are instructed to collect study material from the store office.", imageUrl: "" }
            ],
            staff: [
                { id: 1, name: "[Faculty Name]", role: "Principal / Headmaster", qual: "M.A, M.Ed", photoUrl: "" },
                { id: 2, name: "[Faculty Name]", role: "Lecturer Physics", qual: "M.Sc Physics", photoUrl: "" },
                { id: 3, name: "[Faculty Name]", role: "Teacher General", qual: "B.Sc, B.Ed", photoUrl: "" }
            ],
            facilities: [
                { id: 1, title: "Science Laboratory", desc: "Equipped setup for Physics, Chemistry, and Biology practical demonstrations.", imageUrl: "" },
                { id: 2, title: "Computer Lab & ICT Unit", desc: "Computer literacy setup equipped for ICT education.", imageUrl: "" },
                { id: 3, title: "School Library", desc: "Collection of curriculum textbooks, reference guides, and reading materials.", imageUrl: "" }
            ],
            links: [
                { id: 1, title: "UT Ladakh Official Administration Portal", url: "https://ladakh.nic.in", iconUrl: "" },
                { id: 2, title: "District Kargil Official Portal", url: "https://kargil.nic.in", iconUrl: "" },
                { id: 3, title: "Directorate of School Education Ladakh", url: "#", iconUrl: "" }
            ],
            gallery: [
                { id: 1, title: "School Campus Grounds", url: "https://images.unsplash.com/photo-1580582932707-520aed937b7b?q=80&w=800&auto=format&fit=crop" },
                { id: 2, title: "Classroom Learning Environment", url: "https://images.unsplash.com/photo-1509062522246-3755977927d7?q=80&w=800&auto=format&fit=crop" },
                { id: 3, title: "Library & Study Resource Center", url: "https://images.unsplash.com/photo-1577896851231-70ef18881754?q=80&w=800&auto=format&fit=crop" }
            ],
            profile: {
                basic: [
                    { id: 1, label: "School Name", value: "GOVERNMENT GIRLS HIGHER SECONDARY SCHOOL HAGNIS" },
                    { id: 2, label: "School Code / UDISE Code", value: "[Editable UDISE Code]" },
                    { id: 3, label: "Department", value: "Department of School Education, UT Ladakh" },
                    { id: 4, label: "School Category", value: "Girls Higher Secondary School (Classes 9th to 12th)" },
                    { id: 5, label: "PIN Code", value: "194109" },
                    { id: 6, label: "Medium of Instruction", value: "English / Hindi / Urdu" },
                    { id: 7, label: "Year of Establishment", value: "[Year]" },
                    { id: 8, label: "Village / Location", value: "Hagnis, Chiktan" },
                    { id: 9, label: "District / UT", value: "Kargil, Union Territory of Ladakh" }
                ],
                geo: [
                    { id: 1, label: "Latitude", value: "[Editable Coordinate]" },
                    { id: 2, label: "Longitude", value: "[Editable Coordinate]" },
                    { id: 3, label: "Elevation / Altitude", value: "[Editable Altitude]" },
                    { id: 4, label: "Block / Zone", value: "Chiktan Block" },
                    { id: 5, label: "Nearest Landmark", value: "[Editable Landmark Details]" }
                ],
                infra: [
                    { id: 1, label: "Total School Land Area", value: "[Editable Land Area]" },
                    { id: 2, label: "Built-up Area", value: "[Editable Built-up Area]" },
                    { id: 3, label: "Number of Buildings", value: "[Editable Count]" },
                    { id: 4, label: "Building Floors", value: "Ground + Upper Floors" },
                    { id: 5, label: "Classrooms", value: "[Editable Classroom Count]" },
                    { id: 6, label: "Science / Computer Labs", value: "Functional Labs Available" },
                    { id: 7, label: "Drinking Water Facility", value: "Functional Tap Water Supply" },
                    { id: 8, label: "Sanitation Facilities", value: "Dedicated Girls' Toilets" },
                    { id: 9, label: "Compound Wall", value: "Secured Boundary Wall Present" }
                ]
            },
            events: [
                { id: 1, title: "National Day Celebrations", tag: "CULTURAL & NATIONAL", desc: "Observance of Independence Day, Republic Day, and Ladakh UT Foundation Day with student speeches and cultural shows." },
                { id: 2, title: "Science Exhibition & Quiz Competitions", tag: "ACADEMIC & SCIENCE", desc: "Encouraging innovative science projects and competitive academic spirit among girls." }
            ],
            documents: [
                { id: 1, name: "Student Enrollment Application Form", category: "Admissions", format: "PDF", url: "" },
                { id: 2, name: "Academic Calendar & Board Exam Datesheet", category: "Academics", format: "PDF", url: "" },
                { id: 3, name: "School Conduct & Code of Discipline", category: "General", format: "PDF", url: "" }
            ]
        };

        let appState = JSON.parse(localStorage.getItem('gghss_hagnis_state')) || DEFAULT_STATE;

        // Backfill fields for any state saved before photo-upload support existed
        if (!appState.config.logoUrl && appState.config.logoUrl !== "") appState.config.logoUrl = "";
        if (appState.config.principalPhotoUrl === undefined) appState.config.principalPhotoUrl = "";
        appState.notices.forEach(n => { if (n.imageUrl === undefined) n.imageUrl = ""; });
        appState.staff.forEach(s => { if (s.photoUrl === undefined) s.photoUrl = ""; });
        appState.facilities.forEach(f => { if (f.imageUrl === undefined) f.imageUrl = ""; });
        appState.links.forEach(l => { if (l.iconUrl === undefined) l.iconUrl = ""; });
        if (!appState.profile) appState.profile = JSON.parse(JSON.stringify(DEFAULT_STATE.profile));
        if (!appState.events) appState.events = JSON.parse(JSON.stringify(DEFAULT_STATE.events));
        if (!appState.documents) appState.documents = JSON.parse(JSON.stringify(DEFAULT_STATE.documents));
        appState.documents.forEach(d => { if (d.url === undefined) d.url = ""; });

        // Temporary holders for photos picked in "Add New" admin forms (item doesn't exist yet)
        let tempStaffPhoto = "";
        let tempFacilityPhoto = "";
        let tempNoticePhoto = "";
        let tempLinkPhoto = "";
        let tempGalleryPhoto = "";

        function saveState() {
            localStorage.setItem('gghss_hagnis_state', JSON.stringify(appState));
            renderApp();
        }

        // Shared helper: read a chosen file as a Base64 Data URL, then hand it to a callback
        function readImageFile(inputEl, callback) {
            const file = inputEl.files && inputEl.files[0];
            if (!file) return;
            if (!file.type.startsWith('image/')) {
                alert('Please select a valid image file.');
                return;
            }
            const reader = new FileReader();
            reader.onload = (e) => callback(e.target.result);
            reader.readAsDataURL(file);
        }

        function showPreview(imgEl, dataUrl) {
            imgEl.src = dataUrl;
            imgEl.style.display = 'block';
        }

        // NAVIGATION LOGIC
        function navigateTo(pageId) {
            document.querySelectorAll('.page-view').forEach(p => p.classList.remove('active'));
            const target = document.getElementById('page-' + pageId);
            if (target) target.classList.add('active');

            document.querySelectorAll('.nav-link').forEach(l => l.classList.remove('active'));
            const activeLink = document.querySelector(`.nav-link[href="#${pageId}"]`);
            if (activeLink) activeLink.classList.add('active');

            window.scrollTo({ top: 0, behavior: 'smooth' });
            document.getElementById('main-nav').classList.remove('show');
        }

        function toggleMobileNav() {
            document.getElementById('main-nav').classList.toggle('show');
        }

        // AUTHENTICATION LOGIC
        function openAdminAuth() {
            if (appState.isAdminLoggedIn) {
                toggleAdminPanelVisibility();
            } else {
                document.getElementById('admin-login-modal').classList.add('active');
            }
        }

        function closeAdminAuth() {
            document.getElementById('admin-login-modal').classList.remove('active');
            document.getElementById('login-error').style.display = 'none';
        }

        function processAdminLogin() {
            const uid = document.getElementById('login-userid').value;
            const pass = document.getElementById('login-password').value;

            if (uid === 'GHSSadmin' && pass === 'GHSShagnis123') {
                appState.isAdminLoggedIn = true;
                saveState();
                closeAdminAuth();
                document.getElementById('admin-panel').classList.add('active');
                alert('Admin Authentication Successful! Full content control - including photo uploads - is now unlocked.');
            } else {
                document.getElementById('login-error').style.display = 'block';
            }
        }

        function logoutAdmin() {
            appState.isAdminLoggedIn = false;
            saveState();
            document.getElementById('admin-panel').classList.remove('active');
            alert('Logged out from Admin Dashboard.');
        }

        function toggleAdminPanelVisibility() {
            const panel = document.getElementById('admin-panel');
            panel.classList.toggle('active');
        }

        function switchAdminTab(tabName) {
            document.querySelectorAll('.admin-nav-item').forEach(i => i.classList.remove('active'));
            event.currentTarget.classList.add('active');

            document.querySelectorAll('.admin-tab-pane').forEach(p => p.style.display = 'none');
            document.getElementById('admin-tab-' + tabName).style.display = 'block';
        }

        function switchProfileTab(btn, contentId) {
            document.querySelectorAll('.tab-btn').forEach(b => b.classList.remove('active'));
            btn.classList.add('active');

            document.querySelectorAll('.profile-tab-content').forEach(c => c.style.display = 'none');
            document.getElementById(contentId).style.display = 'block';
        }

        // ===================== PHOTO UPLOAD HANDLERS =====================

        // General Settings: logo + principal photo (existing single records, so update immediately)
        function handleLogoUpload(inputEl) {
            readImageFile(inputEl, (dataUrl) => {
                appState.config.logoUrl = dataUrl;
                showPreview(document.getElementById('cfg-logo-preview'), dataUrl);
            });
        }

        function handlePrincipalPhotoUpload(inputEl) {
            readImageFile(inputEl, (dataUrl) => {
                appState.config.principalPhotoUrl = dataUrl;
                showPreview(document.getElementById('cfg-principal-photo-preview'), dataUrl);
            });
        }

        // Add-new forms: stash the photo in a temp variable until the record is created
        function handleStaffPhotoSelect(inputEl) {
            readImageFile(inputEl, (dataUrl) => {
                tempStaffPhoto = dataUrl;
                showPreview(document.getElementById('adm-staff-photo-preview'), dataUrl);
            });
        }

        function handleFacilityPhotoSelect(inputEl) {
            readImageFile(inputEl, (dataUrl) => {
                tempFacilityPhoto = dataUrl;
                showPreview(document.getElementById('adm-fac-photo-preview'), dataUrl);
            });
        }

        function handleNoticePhotoSelect(inputEl) {
            readImageFile(inputEl, (dataUrl) => {
                tempNoticePhoto = dataUrl;
                showPreview(document.getElementById('adm-notice-photo-preview'), dataUrl);
            });
        }

        function handleLinkPhotoSelect(inputEl) {
            readImageFile(inputEl, (dataUrl) => {
                tempLinkPhoto = dataUrl;
                showPreview(document.getElementById('adm-link-photo-preview'), dataUrl);
            });
        }

        function handleGalleryPhotoSelect(inputEl) {
            readImageFile(inputEl, (dataUrl) => {
                tempGalleryPhoto = dataUrl;
                showPreview(document.getElementById('adm-gal-photo-preview'), dataUrl);
            });
        }

        // ===================== CMS UPDATE FUNCTIONS =====================

        function saveGeneralConfig() {
            appState.config.phone = document.getElementById('cfg-phone').value || appState.config.phone;
            appState.config.email = document.getElementById('cfg-email').value || appState.config.email;
            appState.config.ticker = document.getElementById('cfg-ticker').value || appState.config.ticker;
            appState.config.principalName = document.getElementById('cfg-principal').value || appState.config.principalName;
            appState.config.principalMsg = document.getElementById('cfg-principal-msg').value || appState.config.principalMsg;
            saveState();
            alert('General Settings Updated!');
        }

        function addNoticeFromAdmin() {
            const title = document.getElementById('adm-notice-title').value;
            const category = document.getElementById('adm-notice-cat').value;
            const body = document.getElementById('adm-notice-body').value;

            if (!title) return alert('Notice title required');

            appState.notices.unshift({
                id: Date.now(),
                title,
                category,
                body,
                date: new Date().getDate().toString().padStart(2, '0'),
                month: "NOW",
                imageUrl: tempNoticePhoto
            });
            saveState();
            alert('Notice Published!');
            document.getElementById('adm-notice-title').value = '';
            document.getElementById('adm-notice-body').value = '';
            document.getElementById('adm-notice-photo-file').value = '';
            document.getElementById('adm-notice-photo-preview').style.display = 'none';
            tempNoticePhoto = "";
        }

        function deleteNotice(id) {
            if (confirm('Delete this notice?')) {
                appState.notices = appState.notices.filter(n => n.id !== id);
                saveState();
            }
        }

        function addStaffFromAdmin() {
            const name = document.getElementById('adm-staff-name').value;
            const role = document.getElementById('adm-staff-role').value;
            const qual = document.getElementById('adm-staff-qual').value;

            if (!name) return alert('Name required');

            appState.staff.push({ id: Date.now(), name, role, qual, photoUrl: tempStaffPhoto });
            saveState();
            alert('Staff Member Added!');
            document.getElementById('adm-staff-name').value = '';
            document.getElementById('adm-staff-role').value = '';
            document.getElementById('adm-staff-qual').value = '';
            document.getElementById('adm-staff-photo-file').value = '';
            document.getElementById('adm-staff-photo-preview').style.display = 'none';
            tempStaffPhoto = "";
        }

        function deleteStaff(id) {
            if (confirm('Remove staff entry?')) {
                appState.staff = appState.staff.filter(s => s.id !== id);
                saveState();
            }
        }

        function addFacilityFromAdmin() {
            const title = document.getElementById('adm-fac-title').value;
            const desc = document.getElementById('adm-fac-desc').value;

            if (!title) return alert('Title required');

            appState.facilities.push({ id: Date.now(), title, desc, imageUrl: tempFacilityPhoto });
            saveState();
            alert('Facility Added!');
            document.getElementById('adm-fac-title').value = '';
            document.getElementById('adm-fac-desc').value = '';
            document.getElementById('adm-fac-photo-file').value = '';
            document.getElementById('adm-fac-photo-preview').style.display = 'none';
            tempFacilityPhoto = "";
        }

        function deleteFacility(id) {
            if (confirm('Remove this facility?')) {
                appState.facilities = appState.facilities.filter(f => f.id !== id);
                saveState();
            }
        }

        function addLinkFromAdmin() {
            const title = document.getElementById('adm-link-title').value;
            const url = document.getElementById('adm-link-url').value;

            if (!title) return alert('Title required');

            appState.links.push({ id: Date.now(), title, url, iconUrl: tempLinkPhoto });
            saveState();
            alert('Link Added!');
            document.getElementById('adm-link-title').value = '';
            document.getElementById('adm-link-url').value = '';
            document.getElementById('adm-link-photo-file').value = '';
            document.getElementById('adm-link-photo-preview').style.display = 'none';
            tempLinkPhoto = "";
        }

        function deleteLink(id) {
            if (confirm('Remove this link?')) {
                appState.links = appState.links.filter(l => l.id !== id);
                saveState();
            }
        }

        function addGalleryFromAdmin() {
            const title = document.getElementById('adm-gal-title').value;
            const urlField = document.getElementById('adm-gal-url').value;
            const finalUrl = tempGalleryPhoto || urlField;

            if (!title || !finalUrl) return alert('Title and either an uploaded photo or an image URL are required');

            appState.gallery.push({ id: Date.now(), title, url: finalUrl });
            saveState();
            alert('Photo Added to Gallery!');
            document.getElementById('adm-gal-title').value = '';
            document.getElementById('adm-gal-url').value = '';
            document.getElementById('adm-gal-photo-file').value = '';
            document.getElementById('adm-gal-photo-preview').style.display = 'none';
            tempGalleryPhoto = "";
        }

        function deleteGallery(id) {
            if (confirm('Remove this gallery photo?')) {
                appState.gallery = appState.gallery.filter(g => g.id !== id);
                saveState();
            }
        }

        // Switches between Basic / Geographical / Infrastructure sub-panels inside the
        // admin "School Profile" tab, scoped to that panel so it doesn't clash with the
        // public-facing switchProfileTab() tab buttons on the School Profile page.
        function switchAdminProfileSubtab(btn, subtab) {
            const pane = document.getElementById('admin-tab-profile');
            pane.querySelectorAll('.tab-btn').forEach(b => b.classList.remove('active'));
            btn.classList.add('active');
            pane.querySelectorAll('.admin-profile-subtab').forEach(s => s.style.display = 'none');
            document.getElementById('admin-profile-' + subtab).style.display = 'block';
        }

        function addProfileField(cat) {
            const labelEl = document.getElementById('adm-profile-' + cat + '-label');
            const valueEl = document.getElementById('adm-profile-' + cat + '-value');
            const label = labelEl.value;
            const value = valueEl.value;
            if (!label) return alert('Field label required');

            appState.profile[cat].push({ id: Date.now(), label, value });
            saveState();
            labelEl.value = '';
            valueEl.value = '';
        }

        function updateProfileField(cat, id, newValue) {
            const field = appState.profile[cat].find(f => f.id === id);
            if (field) {
                field.value = newValue;
                localStorage.setItem('gghss_hagnis_state', JSON.stringify(appState));
            }
        }

        function deleteProfileField(cat, id) {
            if (confirm('Remove this field from the School Profile page?')) {
                appState.profile[cat] = appState.profile[cat].filter(f => f.id !== id);
                saveState();
            }
        }

        function addEventFromAdmin() {
            const title = document.getElementById('adm-event-title').value;
            const tag = document.getElementById('adm-event-tag').value;
            const desc = document.getElementById('adm-event-desc').value;

            if (!title) return alert('Event title required');

            appState.events.push({ id: Date.now(), title, tag, desc });
            saveState();
            alert('Event Published!');
            document.getElementById('adm-event-title').value = '';
            document.getElementById('adm-event-desc').value = '';
        }

        function deleteEvent(id) {
            if (confirm('Remove this event?')) {
                appState.events = appState.events.filter(e => e.id !== id);
                saveState();
            }
        }

        function addDocumentFromAdmin() {
            const name = document.getElementById('adm-doc-name').value;
            const category = document.getElementById('adm-doc-category').value;
            const format = document.getElementById('adm-doc-format').value;
            const url = document.getElementById('adm-doc-url').value;

            if (!name || !category) return alert('Document name and category are required');

            appState.documents.push({ id: Date.now(), name, category, format, url });
            saveState();
            alert('Document Added!');
            document.getElementById('adm-doc-name').value = '';
            document.getElementById('adm-doc-category').value = '';
            document.getElementById('adm-doc-url').value = '';
        }

        function deleteDocument(id) {
            if (confirm('Remove this document?')) {
                appState.documents = appState.documents.filter(d => d.id !== id);
                saveState();
            }
        }

        // ===================== RENDER ENGINE =====================
        function renderApp() {
            // Header & Config Bindings
            document.getElementById('top-bar-phone').innerText = appState.config.phone;
            document.getElementById('top-bar-email').innerText = appState.config.email;
            document.getElementById('contact-info-phone').innerText = appState.config.phone;
            document.getElementById('contact-info-email').innerText = appState.config.email;
            document.getElementById('announcement-ticker').innerText = appState.config.ticker;
            document.getElementById('stat-est').innerText = appState.config.est;
            document.getElementById('stat-students').innerText = appState.config.students;
            document.getElementById('stat-faculty').innerText = appState.config.faculty;
            document.getElementById('principal-name').innerText = appState.config.principalName;
            document.getElementById('principal-message').innerText = `"${appState.config.principalMsg}"`;

            // School logo (image if uploaded, else default icon)
            const logoHolder = document.getElementById('school-logo-holder');
            logoHolder.innerHTML = appState.config.logoUrl
                ? `<img src="${appState.config.logoUrl}" alt="School Logo">`
                : `<i class="fa-solid fa-graduation-cap"></i>`;

            // Principal photo (image if uploaded, else default icon)
            const principalHolder = document.getElementById('principal-photo-holder');
            principalHolder.innerHTML = appState.config.principalPhotoUrl
                ? `<img src="${appState.config.principalPhotoUrl}" alt="Principal Photo" style="width:100%; height:100%; object-fit:cover;">`
                : `<i class="fa-solid fa-user-tie"></i>`;

            const adminBtn = document.getElementById('admin-toggle-btn');
            if (appState.isAdminLoggedIn) {
                adminBtn.innerHTML = `<i class="fa-solid fa-sliders"></i> Admin CMS`;
                adminBtn.style.background = `var(--accent-orange)`;
            } else {
                adminBtn.innerHTML = `<i class="fa-solid fa-lock"></i> Admin Login`;
                adminBtn.style.background = `var(--secondary-teal)`;
            }

            // Sync Form Controls
            document.getElementById('cfg-phone').value = appState.config.phone;
            document.getElementById('cfg-email').value = appState.config.email;
            document.getElementById('cfg-ticker').value = appState.config.ticker;
            document.getElementById('cfg-principal').value = appState.config.principalName;
            document.getElementById('cfg-principal-msg').value = appState.config.principalMsg;
            if (appState.config.logoUrl) showPreview(document.getElementById('cfg-logo-preview'), appState.config.logoUrl);
            if (appState.config.principalPhotoUrl) showPreview(document.getElementById('cfg-principal-photo-preview'), appState.config.principalPhotoUrl);

            // Render Notices
            const homeNoticeList = document.getElementById('home-notice-list');
            const fullNoticeList = document.getElementById('full-notice-list');
            const admNoticeManageList = document.getElementById('adm-notice-manage-list');
            homeNoticeList.innerHTML = '';
            fullNoticeList.innerHTML = '';
            admNoticeManageList.innerHTML = '';

            appState.notices.forEach((n, idx) => {
                const badgeClass = n.category === 'urgent' ? 'badge-urgent' : (n.category === 'academic' ? 'badge-academic' : 'badge-general');
                const noticeImageHtml = n.imageUrl ? `<img src="${n.imageUrl}" class="notice-image" alt="${n.title}">` : '';
                const adminDeleteBtn = appState.isAdminLoggedIn ? `<button onclick="deleteNotice(${n.id})" class="btn btn-danger btn-sm" style="margin-top: 0.3rem;"><i class="fa-solid fa-trash"></i> Delete</button>` : '';

                const html = `
                    <div class="notice-card">
                        <div class="notice-date">
                            <div class="day">${n.date}</div>
                            <div class="month">${n.month}</div>
                        </div>
                        <div class="notice-info">
                            <span class="notice-badge ${badgeClass}">${n.category}</span>
                            <h4>${n.title}</h4>
                            ${noticeImageHtml}
                            <p>${n.body}</p>
                            ${adminDeleteBtn}
                        </div>
                    </div>
                `;
                if (idx < 3) homeNoticeList.innerHTML += html;
                fullNoticeList.innerHTML += html;

                if (appState.isAdminLoggedIn) {
                    const thumb = n.imageUrl ? `<img src="${n.imageUrl}" class="item-thumb">` : '';
                    admNoticeManageList.innerHTML += `
                        <div class="notice-card" style="background:#0F172A; border-color:#334155; border-radius: var(--radius-sm); margin-bottom: 0.5rem;">
                            ${thumb}
                            <div class="notice-info">
                                <h4 style="color:#F8FAFC;">${n.title}</h4>
                                <p style="color:#94A3B8;">${n.category.toUpperCase()}</p>
                            </div>
                            <button onclick="deleteNotice(${n.id})" class="btn btn-danger btn-sm"><i class="fa-solid fa-trash"></i></button>
                        </div>
                    `;
                }
            });

            // Render Faculty
            const facultyGrid = document.getElementById('faculty-grid');
            const admStaffManageList = document.getElementById('adm-staff-manage-list');
            facultyGrid.innerHTML = '';
            admStaffManageList.innerHTML = '';
            appState.staff.forEach(s => {
                const deleteBtn = appState.isAdminLoggedIn ? `<button onclick="deleteStaff(${s.id})" class="btn btn-danger btn-sm" style="margin-top: 0.5rem;"><i class="fa-solid fa-trash"></i> Delete</button>` : '';
                const photoHtml = s.photoUrl
                    ? `<img src="${s.photoUrl}" class="faculty-img" alt="${s.name}">`
                    : `<div class="faculty-img" style="background: var(--primary-navy); color: #FFF; display: flex; align-items: center; justify-content: center; font-size: 2.5rem;"><i class="fa-solid fa-user"></i></div>`;
                facultyGrid.innerHTML += `
                    <div class="card card-body faculty-card">
                        ${photoHtml}
                        <h3>${s.name}</h3>
                        <div class="designation">${s.role}</div>
                        <div class="meta">${s.qual}</div>
                        ${deleteBtn}
                    </div>
                `;

                if (appState.isAdminLoggedIn) {
                    const thumb = s.photoUrl ? `<img src="${s.photoUrl}" class="item-thumb">` : '';
                    admStaffManageList.innerHTML += `
                        <div style="display:flex; align-items:center; justify-content:space-between; background:#0F172A; border:1px solid #334155; border-radius: var(--radius-sm); padding: 0.6rem 0.9rem; margin-bottom: 0.5rem;">
                            <div style="display:flex; align-items:center;">${thumb}<span>${s.name} — ${s.role}</span></div>
                            <button onclick="deleteStaff(${s.id})" class="btn btn-danger btn-sm"><i class="fa-solid fa-trash"></i></button>
                        </div>
                    `;
                }
            });

            // Render Facilities
            const facilitiesGrid = document.getElementById('facilities-grid');
            const admFacilityManageList = document.getElementById('adm-facility-manage-list');
            facilitiesGrid.innerHTML = '';
            admFacilityManageList.innerHTML = '';
            appState.facilities.forEach(f => {
                const deleteBtn = appState.isAdminLoggedIn ? `<button onclick="deleteFacility(${f.id})" class="btn btn-danger btn-sm" style="margin-top: 0.5rem;"><i class="fa-solid fa-trash"></i> Delete</button>` : '';
                const imgHtml = f.imageUrl ? `<img src="${f.imageUrl}" class="facility-img" alt="${f.title}">` : '';
                facilitiesGrid.innerHTML += `
                    <div class="card card-body">
                        ${imgHtml}
                        <div style="font-size: 1.8rem; color: var(--secondary-teal); margin-bottom: 0.75rem;"><i class="fa-solid fa-building-columns"></i></div>
                        <h3 style="color: var(--primary-navy); margin-bottom: 0.5rem;">${f.title}</h3>
                        <p style="color: var(--text-muted); font-size: 0.88rem;">${f.desc}</p>
                        ${deleteBtn}
                    </div>
                `;

                if (appState.isAdminLoggedIn) {
                    const thumb = f.imageUrl ? `<img src="${f.imageUrl}" class="item-thumb">` : '';
                    admFacilityManageList.innerHTML += `
                        <div style="display:flex; align-items:center; justify-content:space-between; background:#0F172A; border:1px solid #334155; border-radius: var(--radius-sm); padding: 0.6rem 0.9rem; margin-bottom: 0.5rem;">
                            <div style="display:flex; align-items:center;">${thumb}<span>${f.title}</span></div>
                            <button onclick="deleteFacility(${f.id})" class="btn btn-danger btn-sm"><i class="fa-solid fa-trash"></i></button>
                        </div>
                    `;
                }
            });

            // Render Links
            const linksGrid = document.getElementById('links-grid');
            const admLinkManageList = document.getElementById('adm-link-manage-list');
            linksGrid.innerHTML = '';
            admLinkManageList.innerHTML = '';
            appState.links.forEach(l => {
                const deleteBtn = appState.isAdminLoggedIn ? `<button onclick="deleteLink(${l.id})" class="btn btn-danger btn-sm" style="margin-left: 0.5rem;"><i class="fa-solid fa-trash"></i></button>` : '';
                const iconHtml = l.iconUrl
                    ? `<img src="${l.iconUrl}" style="width:48px; height:48px; object-fit:cover; border-radius:8px; margin-bottom:0.5rem;" alt="${l.title}">`
                    : '';
                linksGrid.innerHTML += `
                    <div class="card card-body">
                        ${iconHtml}
                        <h4 style="color: var(--primary-navy); margin-bottom: 0.5rem;">${l.title}</h4>
                        <a href="${l.url}" target="_blank" class="btn btn-outline btn-sm"><i class="fa-solid fa-arrow-up-right-from-square"></i> Visit Link</a>
                        ${deleteBtn}
                    </div>
                `;

                if (appState.isAdminLoggedIn) {
                    const thumb = l.iconUrl ? `<img src="${l.iconUrl}" class="item-thumb">` : '';
                    admLinkManageList.innerHTML += `
                        <div style="display:flex; align-items:center; justify-content:space-between; background:#0F172A; border:1px solid #334155; border-radius: var(--radius-sm); padding: 0.6rem 0.9rem; margin-bottom: 0.5rem;">
                            <div style="display:flex; align-items:center;">${thumb}<span>${l.title}</span></div>
                            <button onclick="deleteLink(${l.id})" class="btn btn-danger btn-sm"><i class="fa-solid fa-trash"></i></button>
                        </div>
                    `;
                }
            });

            // Render Gallery
            const galleryGrid = document.getElementById('gallery-grid-container');
            const admGalleryManageList = document.getElementById('adm-gallery-manage-list');
            galleryGrid.innerHTML = '';
            admGalleryManageList.innerHTML = '';
            appState.gallery.forEach(g => {
                const deleteBtn = appState.isAdminLoggedIn ? `<button onclick="deleteGallery(${g.id})" class="btn btn-danger btn-sm" style="margin-top: 0.5rem;"><i class="fa-solid fa-trash"></i> Delete</button>` : '';
                galleryGrid.innerHTML += `
                    <div class="gallery-item">
                        <img src="${g.url}" alt="${g.title}">
                        <div class="gallery-overlay">
                            <h4>${g.title}</h4>
                            <p style="font-size: 0.8rem;">Campus Life</p>
                            ${deleteBtn}
                        </div>
                    </div>
                `;

                if (appState.isAdminLoggedIn) {
                    admGalleryManageList.innerHTML += `
                        <div style="display:flex; align-items:center; justify-content:space-between; background:#0F172A; border:1px solid #334155; border-radius: var(--radius-sm); padding: 0.6rem 0.9rem; margin-bottom: 0.5rem;">
                            <div style="display:flex; align-items:center;"><img src="${g.url}" class="item-thumb"><span>${g.title}</span></div>
                            <button onclick="deleteGallery(${g.id})" class="btn btn-danger btn-sm"><i class="fa-solid fa-trash"></i></button>
                        </div>
                    `;
                }
            });

            // Render School Profile (Basic / Geographical / Infrastructure)
            const profileCats = ['basic', 'geo', 'infra'];
            profileCats.forEach(cat => {
                const publicBody = document.getElementById('prof-' + cat + '-body');
                const adminList = document.getElementById('adm-profile-' + cat + '-list');
                publicBody.innerHTML = '';
                adminList.innerHTML = '';

                appState.profile[cat].forEach(f => {
                    publicBody.innerHTML += `<tr><th>${f.label}</th><td>${f.value}</td></tr>`;

                    if (appState.isAdminLoggedIn) {
                        adminList.innerHTML += `
                            <div style="display:flex; align-items:center; gap:0.5rem; background:#0F172A; border:1px solid #334155; border-radius: var(--radius-sm); padding: 0.6rem 0.9rem; margin-bottom: 0.5rem;">
                                <span style="flex: 0 0 40%; color:#94A3B8; font-size:0.85rem;">${f.label}</span>
                                <input type="text" class="form-control" style="margin:0;" value="${f.value.replace(/"/g, '&quot;')}" onchange="updateProfileField('${cat}', ${f.id}, this.value)">
                                <button onclick="deleteProfileField('${cat}', ${f.id})" class="btn btn-danger btn-sm"><i class="fa-solid fa-trash"></i></button>
                            </div>
                        `;
                    }
                });
            });

            // Render Events
            const eventTagColors = {
                'CULTURAL & NATIONAL': 'var(--secondary-teal)',
                'ACADEMIC & SCIENCE': 'var(--accent-orange)',
                'SPORTS & ATHLETICS': 'var(--ladakh-red)',
                'GENERAL': 'var(--primary-navy)'
            };
            const eventsGrid = document.getElementById('events-grid');
            const admEventManageList = document.getElementById('adm-event-manage-list');
            eventsGrid.innerHTML = '';
            admEventManageList.innerHTML = '';
            appState.events.forEach(ev => {
                const tagColor = eventTagColors[ev.tag] || 'var(--secondary-teal)';
                const deleteBtn = appState.isAdminLoggedIn ? `<button onclick="deleteEvent(${ev.id})" class="btn btn-danger btn-sm" style="margin-top: 0.5rem;"><i class="fa-solid fa-trash"></i> Delete</button>` : '';
                eventsGrid.innerHTML += `
                    <div class="card card-body">
                        <span style="font-size: 0.8rem; font-weight: 700; color: ${tagColor};">${ev.tag}</span>
                        <h3 style="color: var(--primary-navy); margin: 0.5rem 0;">${ev.title}</h3>
                        <p style="color: var(--text-muted); font-size: 0.9rem;">${ev.desc}</p>
                        ${deleteBtn}
                    </div>
                `;

                if (appState.isAdminLoggedIn) {
                    admEventManageList.innerHTML += `
                        <div style="display:flex; align-items:center; justify-content:space-between; background:#0F172A; border:1px solid #334155; border-radius: var(--radius-sm); padding: 0.6rem 0.9rem; margin-bottom: 0.5rem;">
                            <div><span>${ev.title}</span><br><span style="color:#94A3B8; font-size:0.8rem;">${ev.tag}</span></div>
                            <button onclick="deleteEvent(${ev.id})" class="btn btn-danger btn-sm"><i class="fa-solid fa-trash"></i></button>
                        </div>
                    `;
                }
            });

            // Render Documents / Downloads
            const downloadsBody = document.getElementById('downloads-body');
            const admDocumentManageList = document.getElementById('adm-document-manage-list');
            downloadsBody.innerHTML = '';
            admDocumentManageList.innerHTML = '';
            appState.documents.forEach(d => {
                const downloadBtn = d.url
                    ? `<a href="${d.url}" target="_blank" class="btn btn-primary" style="padding: 0.25rem 0.6rem; font-size: 0.8rem;"><i class="fa-solid fa-download"></i> Download</a>`
                    : `<button class="btn btn-primary" style="padding: 0.25rem 0.6rem; font-size: 0.8rem; opacity: 0.6; cursor: not-allowed;" title="No file link added yet" disabled><i class="fa-solid fa-download"></i> Download</button>`;
                downloadsBody.innerHTML += `
                    <tr>
                        <td>${d.name}</td>
                        <td>${d.category}</td>
                        <td>${d.format}</td>
                        <td>${downloadBtn}</td>
                    </tr>
                `;

                if (appState.isAdminLoggedIn) {
                    admDocumentManageList.innerHTML += `
                        <div style="display:flex; align-items:center; justify-content:space-between; background:#0F172A; border:1px solid #334155; border-radius: var(--radius-sm); padding: 0.6rem 0.9rem; margin-bottom: 0.5rem;">
                            <div><span>${d.name}</span><br><span style="color:#94A3B8; font-size:0.8rem;">${d.category} · ${d.format}</span></div>
                            <button onclick="deleteDocument(${d.id})" class="btn btn-danger btn-sm"><i class="fa-solid fa-trash"></i></button>
                        </div>
                    `;
                }
            });
        }

        // URGENT NOTICE POPUP CONTROL
        function showUrgentNoticeModal() {
            if (appState.notices.length > 0) {
                const latest = appState.notices[0];
                document.getElementById('modal-notice-title').innerText = latest.title;
                document.getElementById('modal-notice-desc').innerText = latest.body;
            }
            document.getElementById('urgent-modal').classList.add('active');
        }

        function closeUrgentNoticeModal() {
            if (document.getElementById('chk-dont-show').checked) {
                localStorage.setItem('gghss_hagnis_hide_urgent', 'true');
            }
            document.getElementById('urgent-modal').classList.remove('active');
        }

        // GLOBAL SEARCH
        function handleGlobalSearch() {
            const query = document.getElementById('global-search-input').value.toLowerCase();
            if (query.trim() === "") return;

            if (query.includes('notice') || query.includes('circular')) navigateTo('notices');
            else if (query.includes('staff') || query.includes('teacher') || query.includes('faculty')) navigateTo('faculty');
            else if (query.includes('facility') || query.includes('lab') || query.includes('library')) navigateTo('facilities');
            else if (query.includes('contact') || query.includes('phone') || query.includes('email')) navigateTo('contact');
            else if (query.includes('profile') || query.includes('udise') || query.includes('code')) navigateTo('info');
        }

        function handleContactSubmit(e) {
            e.preventDefault();
            alert('Thank you! Your message has been sent to the school administration office.');
            e.target.reset();
        }

        // INIT
        window.addEventListener('DOMContentLoaded', () => {
            renderApp();
            if (appState.isAdminLoggedIn) {
                document.getElementById('admin-panel').classList.add('active');
            }
            if (!localStorage.getItem('gghss_hagnis_hide_urgent')) {
                setTimeout(showUrgentNoticeModal, 1200);
            }
        });
    </script>
</body>
</html>
