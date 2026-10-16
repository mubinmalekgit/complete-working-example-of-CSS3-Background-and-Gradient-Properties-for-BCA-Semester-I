# complete-working-example-of-CSS3-Background-and-Gradient-Properties-for-BCA-Semester-I

<!DOCTYPE html>
<html>
<head>
    <title>CSS3 Background and Gradient</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f2f5fa;
        }

        header {
            background-color: #172554;
            color: white;
            text-align: center;
            padding: 20px;
        }

        nav {
            background-color: #2563eb;
            padding: 15px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 15px;
            font-weight: bold;
        }

        .banner {
            background-image: linear-gradient(
                to right,
                #2563eb,
                #06b6d4,
                #14b8a6
            );
            color: white;
            text-align: center;
            padding: 60px 20px;
        }

        .banner h1 {
            font-size: 38px;
            margin-bottom: 10px;
        }

        .container {
            padding: 30px;
            text-align: center;
        }

        .card {
            display: inline-block;
            width: 250px;
            margin: 12px;
            padding: 25px;
            border-radius: 12px;
            color: white;
            vertical-align: top;
        }

        .linear-card {
            background-image: linear-gradient(
                to right,
                #7c3aed,
                #ec4899
            );
        }

        .radial-card {
            background-image: radial-gradient(
                circle,
                #fef08a,
                #f97316,
                #dc2626
            );
        }

        .conic-card {
            background-image: conic-gradient(
                #2563eb,
                #06b6d4,
                #22c55e,
                #eab308,
                #2563eb
            );
        }

        .image-demo {
            background-color: #dbeafe;
            background-image: repeating-linear-gradient(
                45deg,
                #dbeafe 0px,
                #dbeafe 15px,
                #93c5fd 15px,
                #93c5fd 30px
            );
            background-repeat: repeat;
            background-position: center;
            background-size: auto;
            padding: 35px;
            margin: 25px auto;
            max-width: 700px;
            border: 2px solid #2563eb;
            border-radius: 10px;
        }

        footer {
            background-color: #172554;
            color: white;
            text-align: center;
            padding: 15px;
        }
    </style>
</head>

<body>

    <header>
        <h2>Web Page Development</h2>
        <p>Learning CSS3 Background Properties</p>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#gradients">Gradients</a>
        <a href="#examples">Examples</a>
    </nav>

    <section class="banner" id="home">
        <h1>Welcome to CSS3</h1>
        <p>Create attractive webpages using background and gradient properties.</p>
    </section>

    <section class="container" id="gradients">
        <h2>Types of CSS Gradients</h2>

        <div class="card linear-card">
            <h3>Linear Gradient</h3>
            <p>Colours blend along a straight line.</p>
        </div>

        <div class="card radial-card">
            <h3>Radial Gradient</h3>
            <p>Colours spread outward from a centre.</p>
        </div>

        <div class="card conic-card">
            <h3>Conic Gradient</h3>
            <p>Colours rotate around a central point.</p>
        </div>
    </section>

    <section class="container" id="examples">
        <h2>Repeating Gradient Background</h2>

        <div class="image-demo">
            <h3>CSS Pattern Example</h3>
            <p>This striped background is generated using CSS.</p>
        </div>
    </section>

    <footer>
        <p>BCA Semester I | CSS3 Practical Example by MM</p>
    </footer>

</body>
</html>

