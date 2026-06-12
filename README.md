```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CubeSat Solar Panels</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 40px;
            background: #f4f4f4;
            color: #222;
        }

        h1, h2 {
            color: #003366;
        }

        .container {
            max-width: 1000px;
            margin: auto;
            background: white;
            padding: 30px;
            border-radius: 10px;
        }

        .badge img {
            margin: 5px;
        }

        .card {
            background: #eef6ff;
            padding: 15px;
            margin: 15px 0;
            border-left: 5px solid #0066cc;
        }

        pre {
            background: #222;
            color: white;
            padding: 15px;
            border-radius: 5px;
        }

        img.main {
            width: 80%;
            display: block;
            margin: auto;
        }

        footer {
            margin-top: 30px;
            text-align: center;
            color: gray;
        }
    </style>

</head>

<body>

<div class="container">

<h1 align="center">
    CubeSat Solar Panels
</h1>

<h3 align="center">
    1U CubeSat engineering model solar panels project
</h3>


<div class="badge" align="center">

<img src="https://img.shields.io/badge/status-development-red?style=for-the-badge">

<img src="https://img.shields.io/badge/version-v0.2-lightgray?style=for-the-badge">

<img src="https://img.shields.io/badge/open-source-hardware-blue?style=for-the-badge">

<img src="https://img.shields.io/badge/license-GPL3-yellow?style=for-the-badge">

</div>


<img class="main"
src="https://github.com/andrempmattos/cubesat-solar-panels/blob/main/documentation/figures/15.png">


<h2>Overview</h2>

<p>
This project contains the design and development of a complete solar
power generation system for a 1U CubeSat engineering model.
The objective is to create a modular solar panel solution for
educational aerospace applications, integration tests and research.
</p>


<h2>Main Features</h2>


<div class="card">

<h3>Solar Energy Generation</h3>

<ul>
<li>High efficiency photovoltaic cells.</li>
<li>Up to 25% efficiency.</li>
<li>Protection diodes against reverse current.</li>
<li>Optimized solar cell distribution.</li>
</ul>

</div>



<div class="card">

<h3>Power Monitoring System</h3>

<ul>
<li>Voltage measurement.</li>
<li>Current measurement.</li>
<li>Temperature monitoring.</li>
<li>MPPT algorithm support.</li>
</ul>

</div>



<div class="card">

<h3>ADCS Support</h3>

<ul>
<li>Accelerometer integration.</li>
<li>Gyroscope support.</li>
<li>Magnetorquer control.</li>
<li>Sun light detection.</li>
<li>Embedded copper coils.</li>
</ul>

</div>



<h2>System Architecture</h2>

<pre>

+----------------+
| Solar Panel X  |
+----------------+

+----------------+
| Solar Panel Y  |
+----------------+

+----------------+
| Solar Panel Z  |
+----------------+

</pre>


<h2>Repository Organization</h2>

<pre>

documentation/
    Technical documentation
    Images and drawings

hardware/
    spx/
    spy/
    spz/

references/
    Datasheets
    User guides

</pre>



<h2>Hardware Requirements</h2>

<ul>
<li>Solar cells.</li>
<li>PCB manufactured boards.</li>
<li>Temperature sensors.</li>
<li>Current sensors.</li>
<li>Microcontroller.</li>
<li>Testing equipment.</li>
</ul>



<h2>Software Tools</h2>

<ul>
<li>KiCad for PCB design.</li>
<li>MATLAB/Python for analysis.</li>
<li>LTspice for simulation.</li>
<li>GitHub for version control.</li>
</ul>



<h2>Testing</h2>

<p>
The prototype requires electrical and mechanical validation:
</p>

<ul>
<li>Voltage and current measurements.</li>
<li>Power generation analysis.</li>
<li>Thermal tests.</li>
<li>Mechanical integration tests.</li>
</ul>



<h2>Future Improvements</h2>

<ul>
<li>Battery management integration.</li>
<li>Radiation protection analysis.</li>
<li>Higher efficiency solar cells.</li>
<li>Flight prototype development.</li>
</ul>



<h2>License</h2>

<p>
This project is open-source hardware under GPLv3 license.
It is intended for educational and research purposes.
</p>



<h2>Contributors</h2>

<ul>
<li>André Mattos</li>
<li>Carlos Lemos</li>
</ul>


<footer>
CubeSat Solar Panels Project © 2026
</footer>


</div>

</body>
</html>
```
