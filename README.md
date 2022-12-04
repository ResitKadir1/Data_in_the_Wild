# Data in the Wild: Wrangling and Visualising Data (Autumn 2022)
Data in the Wild: Wrangling and Visualising Data -Project

#Group project

It's a repository supporting the report for the course : "Data in the Wild: Wrangling and Visualising Data (Autumn 2022)".

## **[Overleaf report link here](https://www.overleaf.com/project/63417ff0607b6d26b51b4e5e "Overleaf link")**.


## Dataset

--> Data Sources:

## Data Gathering

-->

## Data Cleaning 


## EDA(Exploratory Data Analysis) & Data Visualisation




##

Almost out of storage … If you run out, you can't create or edit files, send or receive emails on Gmail, or back up to Google Photos.
<!DOCTYPE html>
<head>    
    <meta http-equiv="content-type" content="text/html; charset=UTF-8" />
    
        <script>
            L_NO_TOUCH = false;
            L_DISABLE_3D = false;
        </script>
    
    <style>html, body {width: 100%;height: 100%;margin: 0;padding: 0;}</style>
    <style>#map {position:absolute;top:0;bottom:0;right:0;left:0;}</style>
    <script src="https://cdn.jsdelivr.net/npm/leaflet@1.6.0/dist/leaflet.js"></script>
    <script src="https://code.jquery.com/jquery-1.12.4.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/js/bootstrap.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.js"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/leaflet@1.6.0/dist/leaflet.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap.min.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap-theme.min.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.6.3/css/font-awesome.min.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/python-visualization/folium/folium/templates/leaflet.awesome.rotate.min.css"/>
    
            <meta name="viewport" content="width=device-width,
                initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
            <style>
                #map_f2ccc8c944bbb664ba94eeda529048aa {
                    position: relative;
                    width: 100.0%;
                    height: 100.0%;
                    left: 0.0%;
                    top: 0.0%;
                }
            </style>
        
    <script src="https://cdnjs.cloudflare.com/ajax/libs/leaflet-minimap/3.6.1/Control.MiniMap.js"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/leaflet-minimap/3.6.1/Control.MiniMap.css"/>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/leaflet.markercluster/1.1.0/leaflet.markercluster.js"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/leaflet.markercluster/1.1.0/MarkerCluster.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/leaflet.markercluster/1.1.0/MarkerCluster.Default.css"/>
    <script src="https://cdn.jsdelivr.net/gh/python-visualization/folium@master/folium/templates/leaflet_heat.min.js"></script>
</head>
<body>    
    
            <div class="folium-map" id="map_f2ccc8c944bbb664ba94eeda529048aa" ></div>
        
</body>
<script>    
    
            var map_f2ccc8c944bbb664ba94eeda529048aa = L.map(
                "map_f2ccc8c944bbb664ba94eeda529048aa",
                {
                    center: [55.69903786625288, 12.484338412295388],
                    crs: L.CRS.EPSG3857,
                    zoom: 12,
                    zoomControl: true,
                    preferCanvas: false,
                }
            );

            

        
    
            var tile_layer_ae93c8c40a83d0afe20d65e4613cabc7 = L.tileLayer(
                "https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png",
                {"attribution": "Data by \u0026copy; \u003ca href=\"http://openstreetmap.org\"\u003eOpenStreetMap\u003c/a\u003e, under \u003ca href=\"http://www.openstreetmap.org/copyright\"\u003eODbL\u003c/a\u003e.", "detectRetina": false, "maxNativeZoom": 18, "maxZoom": 18, "minZoom": 0, "noWrap": false, "opacity": 1, "subdomains": "abc", "tms": false}
            ).addTo(map_f2ccc8c944bbb664ba94eeda529048aa);
        
    
            var tile_layer_39207bb70e67dedf62b24d4bd84972d6 = L.tileLayer(
                "https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png",
                {"attribution": "Data by \u0026copy; \u003ca href=\"http://openstreetmap.org\"\u003eOpenStreetMap\u003c/a\u003e, under \u003ca href=\"http://www.openstreetmap.org/copyright\"\u003eODbL\u003c/a\u003e.", "detectRetina": false, "maxNativeZoom": 18, "maxZoom": 18, "minZoom": 0, "noWrap": false, "opacity": 1, "subdomains": "abc", "tms": false}
            );
            var mini_map_5b916864eb115c4090f91b17e47d91a2 = new L.Control.MiniMap(
                tile_layer_39207bb70e67dedf62b24d4bd84972d6,
                {"autoToggleDisplay": false, "centerFixed": false, "collapsedHeight": 25, "collapsedWidth": 25, "height": 150, "minimized": false, "position": "bottomright", "toggleDisplay": false, "width": 150, "zoomAnimation": false, "zoomLevelOffset": -5}
            );
            map_f2ccc8c944bbb664ba94eeda529048aa.addControl(mini_map_5b916864eb115c4090f91b17e47d91a2);
        
    
            var marker_cluster_6acc92584669eaff7e446472dce773f4 = L.markerClusterGroup(
                {}
            );
            map_f2ccc8c944bbb664ba94eeda529048aa.addLayer(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
            var marker_c98cf173e5adcbf08fd33e00403769c8 = L.marker(
                [55.7055424, 12.4917658],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_c120912ba36e10d225dbc9220e07381c = L.popup({"maxWidth": "100%"});

        
            var html_bde8ac035430407fb2e18e8753b10e2c = $(`<div id="html_bde8ac035430407fb2e18e8753b10e2c" style="width: 100.0%; height: 100.0%;">Year Built: 1954, Price:1.995.000, 62.0 m2 , ZipCode:2700 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_c120912ba36e10d225dbc9220e07381c.setContent(html_bde8ac035430407fb2e18e8753b10e2c);
        

        marker_c98cf173e5adcbf08fd33e00403769c8.bindPopup(popup_c120912ba36e10d225dbc9220e07381c)
        ;

        
    
    
            var marker_7e03b2e55d8bbcea91fb1f5f0e5f4cda = L.marker(
                [55.704052, 12.506398],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_f641340bd7825bd7a43ccf4980e63c86 = L.popup({"maxWidth": "100%"});

        
            var html_1814434d5cf6f40952caa51ed90c381f = $(`<div id="html_1814434d5cf6f40952caa51ed90c381f" style="width: 100.0%; height: 100.0%;">Year Built: 1937, Price:1.995.000, 56.0 m2 , ZipCode:2700 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_f641340bd7825bd7a43ccf4980e63c86.setContent(html_1814434d5cf6f40952caa51ed90c381f);
        

        marker_7e03b2e55d8bbcea91fb1f5f0e5f4cda.bindPopup(popup_f641340bd7825bd7a43ccf4980e63c86)
        ;

        
    
    
            var marker_d41b3ff5099e59b3950060e1ee4c8b8e = L.marker(
                [55.715566, 12.460257],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_1793b05e8d0273bac38e89644d63f2dd = L.popup({"maxWidth": "100%"});

        
            var html_85c0460622c7e4393c02e7643ae08bf9 = $(`<div id="html_85c0460622c7e4393c02e7643ae08bf9" style="width: 100.0%; height: 100.0%;">Year Built: 1958, Price:2.395.000, 73.0 m2 , ZipCode:2700 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_1793b05e8d0273bac38e89644d63f2dd.setContent(html_85c0460622c7e4393c02e7643ae08bf9);
        

        marker_d41b3ff5099e59b3950060e1ee4c8b8e.bindPopup(popup_1793b05e8d0273bac38e89644d63f2dd)
        ;

        
    
    
            var marker_f51d2a8cf6224cfebd7e35379c26b767 = L.marker(
                [55.704547, 12.505199],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_0f8154e99d54904115c09b0c855dbb84 = L.popup({"maxWidth": "100%"});

        
            var html_a7b3211d76cc1b2193efbf4b4c7a00de = $(`<div id="html_a7b3211d76cc1b2193efbf4b4c7a00de" style="width: 100.0%; height: 100.0%;">Year Built: 1936, Price:1.995.000, 64.0 m2 , ZipCode:2700 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_0f8154e99d54904115c09b0c855dbb84.setContent(html_a7b3211d76cc1b2193efbf4b4c7a00de);
        

        marker_f51d2a8cf6224cfebd7e35379c26b767.bindPopup(popup_0f8154e99d54904115c09b0c855dbb84)
        ;

        
    
    
            var marker_addbcf8d3cb05b811dc6b67c3c29cacb = L.marker(
                [55.705151, 12.493101],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_4f71a7ef6f7e3ba01c485edc0617f37b = L.popup({"maxWidth": "100%"});

        
            var html_f45ffa1eea7e98bf3660b99b4152fea2 = $(`<div id="html_f45ffa1eea7e98bf3660b99b4152fea2" style="width: 100.0%; height: 100.0%;">Year Built: 1935, Price:1.990.000, 59.0 m2 , ZipCode:2700 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_4f71a7ef6f7e3ba01c485edc0617f37b.setContent(html_f45ffa1eea7e98bf3660b99b4152fea2);
        

        marker_addbcf8d3cb05b811dc6b67c3c29cacb.bindPopup(popup_4f71a7ef6f7e3ba01c485edc0617f37b)
        ;

        
    
    
            var marker_5b07d6ecd4f9807f1ea791959af2eaf9 = L.marker(
                [55.715312, 12.464026],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_a75b8ee580cd9049dcd3e430064fc8e8 = L.popup({"maxWidth": "100%"});

        
            var html_cee149a1641064982ce625d99d83f111 = $(`<div id="html_cee149a1641064982ce625d99d83f111" style="width: 100.0%; height: 100.0%;">Year Built: 1988, Price:3.150.000, 92.0 m2 , ZipCode:2700 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_a75b8ee580cd9049dcd3e430064fc8e8.setContent(html_cee149a1641064982ce625d99d83f111);
        

        marker_5b07d6ecd4f9807f1ea791959af2eaf9.bindPopup(popup_a75b8ee580cd9049dcd3e430064fc8e8)
        ;

        
    
    
            var marker_072347dd79a7fe8880efb9aacab8deb4 = L.marker(
                [55.71533, 12.458846],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_8f0804a641fe4804e3f6435e065faaaf = L.popup({"maxWidth": "100%"});

        
            var html_faf2501180f21fb6bc2274ce07f42a5d = $(`<div id="html_faf2501180f21fb6bc2274ce07f42a5d" style="width: 100.0%; height: 100.0%;">Year Built: 1958, Price:2.350.000, 87.0 m2 , ZipCode:2700 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_8f0804a641fe4804e3f6435e065faaaf.setContent(html_faf2501180f21fb6bc2274ce07f42a5d);
        

        marker_072347dd79a7fe8880efb9aacab8deb4.bindPopup(popup_8f0804a641fe4804e3f6435e065faaaf)
        ;

        
    
    
            var marker_7b81379aa13709ca06c293de8920fb2f = L.marker(
                [55.715505, 12.459588],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_ee5a2da13efdabef2691a761b343cad1 = L.popup({"maxWidth": "100%"});

        
            var html_26ca424bbb119fb017821faccf09320f = $(`<div id="html_26ca424bbb119fb017821faccf09320f" style="width: 100.0%; height: 100.0%;">Year Built: 1958, Price:2.395.000, 89.0 m2 , ZipCode:2700 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_ee5a2da13efdabef2691a761b343cad1.setContent(html_26ca424bbb119fb017821faccf09320f);
        

        marker_7b81379aa13709ca06c293de8920fb2f.bindPopup(popup_ee5a2da13efdabef2691a761b343cad1)
        ;

        
    
    
            var marker_842b639e46d4c992a84659ce82efae27 = L.marker(
                [55.705985, 12.492822],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_d4ca655c7966a965ddcf82a612d08ee7 = L.popup({"maxWidth": "100%"});

        
            var html_0408ec8b18db164c37c8fbed4847acf3 = $(`<div id="html_0408ec8b18db164c37c8fbed4847acf3" style="width: 100.0%; height: 100.0%;">Year Built: 1959, Price:1.495.000, 41.0 m2 , ZipCode:2700 ,  Rooms:1, HomeType:Ejerlejlighed</div>`)[0];
            popup_d4ca655c7966a965ddcf82a612d08ee7.setContent(html_0408ec8b18db164c37c8fbed4847acf3);
        

        marker_842b639e46d4c992a84659ce82efae27.bindPopup(popup_d4ca655c7966a965ddcf82a612d08ee7)
        ;

        
    
    
            var marker_d6bde264a5c3381ebc5e058e4ff39dc0 = L.marker(
                [55.714389, 12.45938],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_46a2712840ff4c27133fed4ac54094e2 = L.popup({"maxWidth": "100%"});

        
            var html_15de6c4156c364cfde03ac75b71b8f91 = $(`<div id="html_15de6c4156c364cfde03ac75b71b8f91" style="width: 100.0%; height: 100.0%;">Year Built: 1958, Price:2.595.000, 87.0 m2 , ZipCode:2700 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_46a2712840ff4c27133fed4ac54094e2.setContent(html_15de6c4156c364cfde03ac75b71b8f91);
        

        marker_d6bde264a5c3381ebc5e058e4ff39dc0.bindPopup(popup_46a2712840ff4c27133fed4ac54094e2)
        ;

        
    
    
            var marker_04e14e65d0942c9f953618c6215b739b = L.marker(
                [55.704963, 12.494197],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_3303c70b2859fd70d2c77037cd794022 = L.popup({"maxWidth": "100%"});

        
            var html_e7a6596e81db47edfeea75e63f87940a = $(`<div id="html_e7a6596e81db47edfeea75e63f87940a" style="width: 100.0%; height: 100.0%;">Year Built: 1935, Price:1.895.000, 62.0 m2 , ZipCode:2700 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_3303c70b2859fd70d2c77037cd794022.setContent(html_e7a6596e81db47edfeea75e63f87940a);
        

        marker_04e14e65d0942c9f953618c6215b739b.bindPopup(popup_3303c70b2859fd70d2c77037cd794022)
        ;

        
    
    
            var marker_1f441754e3783cd40ca398db31bc0e6c = L.marker(
                [55.702341, 12.498637],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_dabc63bea85e284319839d92a05ad30a = L.popup({"maxWidth": "100%"});

        
            var html_2392a33c55be31dd4dbb5e860defb716 = $(`<div id="html_2392a33c55be31dd4dbb5e860defb716" style="width: 100.0%; height: 100.0%;">Year Built: 1933, Price:3.250.000, 86.0 m2 , ZipCode:2700 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_dabc63bea85e284319839d92a05ad30a.setContent(html_2392a33c55be31dd4dbb5e860defb716);
        

        marker_1f441754e3783cd40ca398db31bc0e6c.bindPopup(popup_dabc63bea85e284319839d92a05ad30a)
        ;

        
    
    
            var marker_d87f43ec0ee3ed2ccfe520ddc7709e45 = L.marker(
                [55.715505, 12.459588],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_8250e119ae20bbb532bdd9060ba5cd41 = L.popup({"maxWidth": "100%"});

        
            var html_cabac7d22c2b05c768d9317132862698 = $(`<div id="html_cabac7d22c2b05c768d9317132862698" style="width: 100.0%; height: 100.0%;">Year Built: 1958, Price:2.095.000, 73.0 m2 , ZipCode:2700 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_8250e119ae20bbb532bdd9060ba5cd41.setContent(html_cabac7d22c2b05c768d9317132862698);
        

        marker_d87f43ec0ee3ed2ccfe520ddc7709e45.bindPopup(popup_8250e119ae20bbb532bdd9060ba5cd41)
        ;

        
    
    
            var marker_8dc37d07123371b4985e86eab3ffec2e = L.marker(
                [55.706657, 12.490357],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_ee74469090358f503929a633ea857a90 = L.popup({"maxWidth": "100%"});

        
            var html_a4d27aa6c60a6597794092707b5ad40f = $(`<div id="html_a4d27aa6c60a6597794092707b5ad40f" style="width: 100.0%; height: 100.0%;">Year Built: 1935, Price:1.775.000, 56.0 m2 , ZipCode:2700 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_ee74469090358f503929a633ea857a90.setContent(html_a4d27aa6c60a6597794092707b5ad40f);
        

        marker_8dc37d07123371b4985e86eab3ffec2e.bindPopup(popup_ee74469090358f503929a633ea857a90)
        ;

        
    
    
            var marker_7e465172af3cab19813ee9563c89563d = L.marker(
                [55.712447, 12.472443],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_d90f1d0c486ef616a9550c71953a54c7 = L.popup({"maxWidth": "100%"});

        
            var html_704dd45a0b8d9fc80167a96be8aafc04 = $(`<div id="html_704dd45a0b8d9fc80167a96be8aafc04" style="width: 100.0%; height: 100.0%;">Year Built: 1930, Price:3.995.000, 144.0 m2 , ZipCode:2700 ,  Rooms:5, HomeType:Ejerlejlighed</div>`)[0];
            popup_d90f1d0c486ef616a9550c71953a54c7.setContent(html_704dd45a0b8d9fc80167a96be8aafc04);
        

        marker_7e465172af3cab19813ee9563c89563d.bindPopup(popup_d90f1d0c486ef616a9550c71953a54c7)
        ;

        
    
    
            var marker_7e9b1344f6d38ec265e62e2955d4ee27 = L.marker(
                [55.7029891, 12.4954996],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_4f5916fa2f6a04d8c65c57935cbce1a4 = L.popup({"maxWidth": "100%"});

        
            var html_4288b70f3ac3d660c13a7756fc4ce38d = $(`<div id="html_4288b70f3ac3d660c13a7756fc4ce38d" style="width: 100.0%; height: 100.0%;">Year Built: 1927, Price:3.950.000, 71.0 m2 , ZipCode:2700 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_4f5916fa2f6a04d8c65c57935cbce1a4.setContent(html_4288b70f3ac3d660c13a7756fc4ce38d);
        

        marker_7e9b1344f6d38ec265e62e2955d4ee27.bindPopup(popup_4f5916fa2f6a04d8c65c57935cbce1a4)
        ;

        
    
    
            var marker_bf3d3f348671d5f47f7532609ce41d5d = L.marker(
                [55.706564, 12.490083],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_4ca47dd8b2c71357172dc0388ae51be7 = L.popup({"maxWidth": "100%"});

        
            var html_66a19fd91f7066b58e2894b5e1387979 = $(`<div id="html_66a19fd91f7066b58e2894b5e1387979" style="width: 100.0%; height: 100.0%;">Year Built: 1932, Price:1.995.000, 56.0 m2 , ZipCode:2700 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_4ca47dd8b2c71357172dc0388ae51be7.setContent(html_66a19fd91f7066b58e2894b5e1387979);
        

        marker_bf3d3f348671d5f47f7532609ce41d5d.bindPopup(popup_4ca47dd8b2c71357172dc0388ae51be7)
        ;

        
    
    
            var marker_62076e3637e48459fb571cdb92481f6a = L.marker(
                [55.703585, 12.488515],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_366bc2e00eabf59291b32cbcde469612 = L.popup({"maxWidth": "100%"});

        
            var html_dcbf923c53de8df35e90a21c042369b9 = $(`<div id="html_dcbf923c53de8df35e90a21c042369b9" style="width: 100.0%; height: 100.0%;">Year Built: 1933, Price:1.895.000, 55.0 m2 , ZipCode:2700 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_366bc2e00eabf59291b32cbcde469612.setContent(html_dcbf923c53de8df35e90a21c042369b9);
        

        marker_62076e3637e48459fb571cdb92481f6a.bindPopup(popup_366bc2e00eabf59291b32cbcde469612)
        ;

        
    
    
            var marker_dc6a991fb5d894e86157ef7b2d5dd149 = L.marker(
                [55.705168, 12.492628],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_76e0aae3c30801c130defbae9b66bf5b = L.popup({"maxWidth": "100%"});

        
            var html_f664446cd74303774d3476f171f63d3b = $(`<div id="html_f664446cd74303774d3476f171f63d3b" style="width: 100.0%; height: 100.0%;">Year Built: 1930, Price:3.145.000, 80.0 m2 , ZipCode:2700 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_76e0aae3c30801c130defbae9b66bf5b.setContent(html_f664446cd74303774d3476f171f63d3b);
        

        marker_dc6a991fb5d894e86157ef7b2d5dd149.bindPopup(popup_76e0aae3c30801c130defbae9b66bf5b)
        ;

        
    
    
            var marker_2c3f84b9716ec56fe6984cb84ebb71c1 = L.marker(
                [55.704164, 12.478625],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_4d3f86f53fe53e336b06708706794aa2 = L.popup({"maxWidth": "100%"});

        
            var html_548b97e4086e02e398422cb2af58feb5 = $(`<div id="html_548b97e4086e02e398422cb2af58feb5" style="width: 100.0%; height: 100.0%;">Year Built: 1947, Price:3.395.000, 93.0 m2 , ZipCode:2700 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_4d3f86f53fe53e336b06708706794aa2.setContent(html_548b97e4086e02e398422cb2af58feb5);
        

        marker_2c3f84b9716ec56fe6984cb84ebb71c1.bindPopup(popup_4d3f86f53fe53e336b06708706794aa2)
        ;

        
    
    
            var marker_5536747a087b3e836c3eb709434e16d0 = L.marker(
                [55.705023, 12.49376],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_fc932cc33ba0f866bb07c2fd52b64db3 = L.popup({"maxWidth": "100%"});

        
            var html_23eeefd4eb8a8c8c186de663a0ff4ea8 = $(`<div id="html_23eeefd4eb8a8c8c186de663a0ff4ea8" style="width: 100.0%; height: 100.0%;">Year Built: 1935, Price:1.995.000, 59.0 m2 , ZipCode:2700 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_fc932cc33ba0f866bb07c2fd52b64db3.setContent(html_23eeefd4eb8a8c8c186de663a0ff4ea8);
        

        marker_5536747a087b3e836c3eb709434e16d0.bindPopup(popup_fc932cc33ba0f866bb07c2fd52b64db3)
        ;

        
    
    
            var marker_cdd522f1f43f48b21161a65ab588e2c3 = L.marker(
                [55.696557, 12.499026],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_0d7aaf2fff58926b390e00f88c9b2906 = L.popup({"maxWidth": "100%"});

        
            var html_cf1984f99d11bae81f18da65e78636c3 = $(`<div id="html_cf1984f99d11bae81f18da65e78636c3" style="width: 100.0%; height: 100.0%;">Year Built: 1934, Price:2.050.000, 54.0 m2 , ZipCode:2700 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_0d7aaf2fff58926b390e00f88c9b2906.setContent(html_cf1984f99d11bae81f18da65e78636c3);
        

        marker_cdd522f1f43f48b21161a65ab588e2c3.bindPopup(popup_0d7aaf2fff58926b390e00f88c9b2906)
        ;

        
    
    
            var marker_87584978ce164d3ac7552744a413d06f = L.marker(
                [55.702759, 12.496397],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_4fab8cba8280f16782150d7edc2a6b40 = L.popup({"maxWidth": "100%"});

        
            var html_36c22960d2256bf573a6277217c8cd0d = $(`<div id="html_36c22960d2256bf573a6277217c8cd0d" style="width: 100.0%; height: 100.0%;">Year Built: 1933, Price:1.695.000, 43.0 m2 , ZipCode:2700 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_4fab8cba8280f16782150d7edc2a6b40.setContent(html_36c22960d2256bf573a6277217c8cd0d);
        

        marker_87584978ce164d3ac7552744a413d06f.bindPopup(popup_4fab8cba8280f16782150d7edc2a6b40)
        ;

        
    
    
            var marker_78e96ac960458e88e16d10b50797241d = L.marker(
                [55.705848, 12.493291],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_05eb4f69422457749e498fdd16af1305 = L.popup({"maxWidth": "100%"});

        
            var html_6496c0402799d6a593ca8e07a3dd4784 = $(`<div id="html_6496c0402799d6a593ca8e07a3dd4784" style="width: 100.0%; height: 100.0%;">Year Built: 1959, Price:2.595.000, 78.0 m2 , ZipCode:2700 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_05eb4f69422457749e498fdd16af1305.setContent(html_6496c0402799d6a593ca8e07a3dd4784);
        

        marker_78e96ac960458e88e16d10b50797241d.bindPopup(popup_05eb4f69422457749e498fdd16af1305)
        ;

        
    
    
            var marker_498eb45aa5b7b1f34d6219bba2d869e1 = L.marker(
                [55.695908, 12.499253],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_7c464f77b931685b3a1a3e6a5dc1c592 = L.popup({"maxWidth": "100%"});

        
            var html_47635cec77e2b090f8a11871669dad90 = $(`<div id="html_47635cec77e2b090f8a11871669dad90" style="width: 100.0%; height: 100.0%;">Year Built: 1934, Price:2.095.000, 54.0 m2 , ZipCode:2700 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_7c464f77b931685b3a1a3e6a5dc1c592.setContent(html_47635cec77e2b090f8a11871669dad90);
        

        marker_498eb45aa5b7b1f34d6219bba2d869e1.bindPopup(popup_7c464f77b931685b3a1a3e6a5dc1c592)
        ;

        
    
    
            var marker_478546fd5ed9fdc84f570d5b6c40558b = L.marker(
                [55.703339, 12.497562],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_b2666a2f7a77cccc5e6afdb8d3df5f5a = L.popup({"maxWidth": "100%"});

        
            var html_17ef24f43d5a73748f07a6add0588305 = $(`<div id="html_17ef24f43d5a73748f07a6add0588305" style="width: 100.0%; height: 100.0%;">Year Built: 1933, Price:3.350.000, 96.0 m2 , ZipCode:2700 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_b2666a2f7a77cccc5e6afdb8d3df5f5a.setContent(html_17ef24f43d5a73748f07a6add0588305);
        

        marker_478546fd5ed9fdc84f570d5b6c40558b.bindPopup(popup_b2666a2f7a77cccc5e6afdb8d3df5f5a)
        ;

        
    
    
            var marker_1df30fa927d0f25d305608487bddde74 = L.marker(
                [55.715566, 12.460257],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_e594f31f8d785bb0d7d359dd7f21793b = L.popup({"maxWidth": "100%"});

        
            var html_d633cf7ba7103334c7c4bcdb68ebf6bf = $(`<div id="html_d633cf7ba7103334c7c4bcdb68ebf6bf" style="width: 100.0%; height: 100.0%;">Year Built: 1958, Price:2.295.000, 90.0 m2 , ZipCode:2700 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_e594f31f8d785bb0d7d359dd7f21793b.setContent(html_d633cf7ba7103334c7c4bcdb68ebf6bf);
        

        marker_1df30fa927d0f25d305608487bddde74.bindPopup(popup_e594f31f8d785bb0d7d359dd7f21793b)
        ;

        
    
    
            var marker_1ef168e55c1fac698ee4713c8082c0b2 = L.marker(
                [55.7044915, 12.4977378],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_fb2e78f205ede3ac1824d2aab109ca01 = L.popup({"maxWidth": "100%"});

        
            var html_28f14e0452862916a62f91ba3484ae3c = $(`<div id="html_28f14e0452862916a62f91ba3484ae3c" style="width: 100.0%; height: 100.0%;">Year Built: 1932, Price:3.895.000, 98.0 m2 , ZipCode:2700 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_fb2e78f205ede3ac1824d2aab109ca01.setContent(html_28f14e0452862916a62f91ba3484ae3c);
        

        marker_1ef168e55c1fac698ee4713c8082c0b2.bindPopup(popup_fb2e78f205ede3ac1824d2aab109ca01)
        ;

        
    
    
            var marker_01634c7a6f10770f211851f9953ac9eb = L.marker(
                [55.706317, 12.489446],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_f3c754389d9d105f775f61a8dbfd302d = L.popup({"maxWidth": "100%"});

        
            var html_19c2dc197684187f93c6dbe20187ad75 = $(`<div id="html_19c2dc197684187f93c6dbe20187ad75" style="width: 100.0%; height: 100.0%;">Year Built: 1932, Price:2.895.000, 83.0 m2 , ZipCode:2700 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_f3c754389d9d105f775f61a8dbfd302d.setContent(html_19c2dc197684187f93c6dbe20187ad75);
        

        marker_01634c7a6f10770f211851f9953ac9eb.bindPopup(popup_f3c754389d9d105f775f61a8dbfd302d)
        ;

        
    
    
            var marker_cc912853bae4c139dc85b16614485aa0 = L.marker(
                [55.7055424, 12.4917658],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_14fc392e9a23e33d6e75f62f5b7edb40 = L.popup({"maxWidth": "100%"});

        
            var html_9eb177aadc946a7439024a8313901ea4 = $(`<div id="html_9eb177aadc946a7439024a8313901ea4" style="width: 100.0%; height: 100.0%;">Year Built: 2006, Price:3.995.000, 116.0 m2 , ZipCode:2700 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_14fc392e9a23e33d6e75f62f5b7edb40.setContent(html_9eb177aadc946a7439024a8313901ea4);
        

        marker_cc912853bae4c139dc85b16614485aa0.bindPopup(popup_14fc392e9a23e33d6e75f62f5b7edb40)
        ;

        
    
    
            var marker_4da1c990f70a9eddbb5f07a2cdac6df0 = L.marker(
                [55.704601, 12.5083865],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_4b3252cc9ce780df7449d976e43e1ce0 = L.popup({"maxWidth": "100%"});

        
            var html_7b857f46f9400c437d0a5555c3b3dbd0 = $(`<div id="html_7b857f46f9400c437d0a5555c3b3dbd0" style="width: 100.0%; height: 100.0%;">Year Built: 1968, Price:1.695.000, 53.0 m2 , ZipCode:2700 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_4b3252cc9ce780df7449d976e43e1ce0.setContent(html_7b857f46f9400c437d0a5555c3b3dbd0);
        

        marker_4da1c990f70a9eddbb5f07a2cdac6df0.bindPopup(popup_4b3252cc9ce780df7449d976e43e1ce0)
        ;

        
    
    
            var marker_b613ee99e2827c70c719205574b1aa2a = L.marker(
                [55.704311, 12.507025],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_75bb47c62fafc768e8d56687ac364f8b = L.popup({"maxWidth": "100%"});

        
            var html_ddb8587532355d90d44fb676f0575b74 = $(`<div id="html_ddb8587532355d90d44fb676f0575b74" style="width: 100.0%; height: 100.0%;">Year Built: 1907, Price:2.595.000, 67.0 m2 , ZipCode:2700 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_75bb47c62fafc768e8d56687ac364f8b.setContent(html_ddb8587532355d90d44fb676f0575b74);
        

        marker_b613ee99e2827c70c719205574b1aa2a.bindPopup(popup_75bb47c62fafc768e8d56687ac364f8b)
        ;

        
    
    
            var marker_22745ecdf703550122c97f60de6f18a1 = L.marker(
                [55.703585, 12.488515],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_d08078c79ef4ab86c44847fe212d6c00 = L.popup({"maxWidth": "100%"});

        
            var html_892646c896f8ffbcdf882fdcbf54ed78 = $(`<div id="html_892646c896f8ffbcdf882fdcbf54ed78" style="width: 100.0%; height: 100.0%;">Year Built: 1933, Price:1.698.000, 47.0 m2 , ZipCode:2700 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_d08078c79ef4ab86c44847fe212d6c00.setContent(html_892646c896f8ffbcdf882fdcbf54ed78);
        

        marker_22745ecdf703550122c97f60de6f18a1.bindPopup(popup_d08078c79ef4ab86c44847fe212d6c00)
        ;

        
    
    
            var marker_b4044abb8a3dede7530bc4dc179a2348 = L.marker(
                [55.706362, 12.489962],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_81399e6aa03efa2908e50521b8e68cad = L.popup({"maxWidth": "100%"});

        
            var html_49e5fa088b20f58a7590865827a73032 = $(`<div id="html_49e5fa088b20f58a7590865827a73032" style="width: 100.0%; height: 100.0%;">Year Built: 1932, Price:1.845.000, 58.0 m2 , ZipCode:2700 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_81399e6aa03efa2908e50521b8e68cad.setContent(html_49e5fa088b20f58a7590865827a73032);
        

        marker_b4044abb8a3dede7530bc4dc179a2348.bindPopup(popup_81399e6aa03efa2908e50521b8e68cad)
        ;

        
    
    
            var marker_a28f9f5ad3c4fd5deb50b7150abc1e49 = L.marker(
                [55.7055424, 12.4917658],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_c58bd59ef1959ae58b016e18b9ea6ab9 = L.popup({"maxWidth": "100%"});

        
            var html_c6e10a293ae68becaa0efd2cc1f79f00 = $(`<div id="html_c6e10a293ae68becaa0efd2cc1f79f00" style="width: 100.0%; height: 100.0%;">Year Built: 1954, Price:3.095.000, 96.0 m2 , ZipCode:2700 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_c58bd59ef1959ae58b016e18b9ea6ab9.setContent(html_c6e10a293ae68becaa0efd2cc1f79f00);
        

        marker_a28f9f5ad3c4fd5deb50b7150abc1e49.bindPopup(popup_c58bd59ef1959ae58b016e18b9ea6ab9)
        ;

        
    
    
            var marker_27b3b567451f1babf37032db8ff2811a = L.marker(
                [55.70426, 12.506643],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_16b079a75ae28da30fd1296c176e837c = L.popup({"maxWidth": "100%"});

        
            var html_578602cdeb2b217e3bb9d2774a1f01a6 = $(`<div id="html_578602cdeb2b217e3bb9d2774a1f01a6" style="width: 100.0%; height: 100.0%;">Year Built: 1937, Price:2.200.000, 55.0 m2 , ZipCode:2700 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_16b079a75ae28da30fd1296c176e837c.setContent(html_578602cdeb2b217e3bb9d2774a1f01a6);
        

        marker_27b3b567451f1babf37032db8ff2811a.bindPopup(popup_16b079a75ae28da30fd1296c176e837c)
        ;

        
    
    
            var marker_a426c405437cc5eb6b14a5ed861b1d4f = L.marker(
                [55.680608, 12.591342],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_70344d65d2d07c8bdb0aa09494497d9c = L.popup({"maxWidth": "100%"});

        
            var html_c21cbdf8dd43d550c5e2de8c68734137 = $(`<div id="html_c21cbdf8dd43d550c5e2de8c68734137" style="width: 100.0%; height: 100.0%;">Year Built: 1918, Price:18.000.000, 145.0 m2 , ZipCode:1051 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_70344d65d2d07c8bdb0aa09494497d9c.setContent(html_c21cbdf8dd43d550c5e2de8c68734137);
        

        marker_a426c405437cc5eb6b14a5ed861b1d4f.bindPopup(popup_70344d65d2d07c8bdb0aa09494497d9c)
        ;

        
    
    
            var marker_278db3faf24a0f2617943e491ea175aa = L.marker(
                [55.67757, 12.588126],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_4757f7015796c187671721aa82560b1f = L.popup({"maxWidth": "100%"});

        
            var html_64751f4ddb993c371c6c42fa2ea3ff71 = $(`<div id="html_64751f4ddb993c371c6c42fa2ea3ff71" style="width: 100.0%; height: 100.0%;">Year Built: 1877, Price:10.295.000, 141.0 m2 , ZipCode:1055 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_4757f7015796c187671721aa82560b1f.setContent(html_64751f4ddb993c371c6c42fa2ea3ff71);
        

        marker_278db3faf24a0f2617943e491ea175aa.bindPopup(popup_4757f7015796c187671721aa82560b1f)
        ;

        
    
    
            var marker_f04a2fb5cdde5b5b270b129b8e28b76c = L.marker(
                [55.677229, 12.588393],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_0f4de4821984db02d26d7bb78d736b07 = L.popup({"maxWidth": "100%"});

        
            var html_938f9efa770ef7ed4e746553b9664f6f = $(`<div id="html_938f9efa770ef7ed4e746553b9664f6f" style="width: 100.0%; height: 100.0%;">Year Built: 1880, Price:13.500.000, 185.0 m2 , ZipCode:1055 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_0f4de4821984db02d26d7bb78d736b07.setContent(html_938f9efa770ef7ed4e746553b9664f6f);
        

        marker_f04a2fb5cdde5b5b270b129b8e28b76c.bindPopup(popup_0f4de4821984db02d26d7bb78d736b07)
        ;

        
    
    
            var marker_89ceca221c171813a23a3516d052eb63 = L.marker(
                [55.677701, 12.582804],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_3d4e8db84972a7576d8f14f8833fb4ea = L.popup({"maxWidth": "100%"});

        
            var html_8d9a8ee50102ff1e8a2cd7ea86b68a2d = $(`<div id="html_8d9a8ee50102ff1e8a2cd7ea86b68a2d" style="width: 100.0%; height: 100.0%;">Year Built: 1798, Price:3.795.000, 68.0 m2 , ZipCode:1063 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_3d4e8db84972a7576d8f14f8833fb4ea.setContent(html_8d9a8ee50102ff1e8a2cd7ea86b68a2d);
        

        marker_89ceca221c171813a23a3516d052eb63.bindPopup(popup_3d4e8db84972a7576d8f14f8833fb4ea)
        ;

        
    
    
            var marker_624749d0841afb86666daa5c57793c3a = L.marker(
                [55.67772, 12.58224],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_d5be12752b0e7d4664099aa25ccd2e87 = L.popup({"maxWidth": "100%"});

        
            var html_2aeba506fc7ae736db7fa861eceedc64 = $(`<div id="html_2aeba506fc7ae736db7fa861eceedc64" style="width: 100.0%; height: 100.0%;">Year Built: 1800, Price:5.395.000, 72.0 m2 , ZipCode:1066 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_d5be12752b0e7d4664099aa25ccd2e87.setContent(html_2aeba506fc7ae736db7fa861eceedc64);
        

        marker_624749d0841afb86666daa5c57793c3a.bindPopup(popup_d5be12752b0e7d4664099aa25ccd2e87)
        ;

        
    
    
            var marker_f14fb57c21fa7b630e5b4f1f20548f05 = L.marker(
                [55.678108, 12.582446],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_d2bfab003405be81b01f3fb655a87ebb = L.popup({"maxWidth": "100%"});

        
            var html_a2061c8527f5706a266c210ce34de0f4 = $(`<div id="html_a2061c8527f5706a266c210ce34de0f4" style="width: 100.0%; height: 100.0%;">Year Built: 1799, Price:5.295.000, 92.0 m2 , ZipCode:1068 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_d2bfab003405be81b01f3fb655a87ebb.setContent(html_a2061c8527f5706a266c210ce34de0f4);
        

        marker_f14fb57c21fa7b630e5b4f1f20548f05.bindPopup(popup_d2bfab003405be81b01f3fb655a87ebb)
        ;

        
    
    
            var marker_be089128e25b1ccd9fe729eb5203a6c6 = L.marker(
                [55.681322, 12.583427],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_d62b1ea5a38ed52dab1354096a5222a9 = L.popup({"maxWidth": "100%"});

        
            var html_7df24152b6764670ab6d82f2d0eebf0a = $(`<div id="html_7df24152b6764670ab6d82f2d0eebf0a" style="width: 100.0%; height: 100.0%;">Year Built: 1800, Price:5.195.000, 70.0 m2 , ZipCode:1104 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_d62b1ea5a38ed52dab1354096a5222a9.setContent(html_7df24152b6764670ab6d82f2d0eebf0a);
        

        marker_be089128e25b1ccd9fe729eb5203a6c6.bindPopup(popup_d62b1ea5a38ed52dab1354096a5222a9)
        ;

        
    
    
            var marker_1b99dd603bc945974cfcfb59250f0723 = L.marker(
                [55.681395, 12.583128],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_d6fb56ea06333b8de24d077884a459f5 = L.popup({"maxWidth": "100%"});

        
            var html_52d502c7cbc9218688eee041afc06b18 = $(`<div id="html_52d502c7cbc9218688eee041afc06b18" style="width: 100.0%; height: 100.0%;">Year Built: 1741, Price:3.995.000, 53.0 m2 , ZipCode:1107 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_d6fb56ea06333b8de24d077884a459f5.setContent(html_52d502c7cbc9218688eee041afc06b18);
        

        marker_1b99dd603bc945974cfcfb59250f0723.bindPopup(popup_d6fb56ea06333b8de24d077884a459f5)
        ;

        
    
    
            var marker_b3a1965cac1b131dfd1fbcb3b6a4dae6 = L.marker(
                [55.683258, 12.578112],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_31c3d7a3d90571bde938e069c6a67157 = L.popup({"maxWidth": "100%"});

        
            var html_cc3763dbf9eb0ee18da0cc6acb3f3917 = $(`<div id="html_cc3763dbf9eb0ee18da0cc6acb3f3917" style="width: 100.0%; height: 100.0%;">Year Built: 1700, Price:4.875.000, 72.0 m2 , ZipCode:1119 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_31c3d7a3d90571bde938e069c6a67157.setContent(html_cc3763dbf9eb0ee18da0cc6acb3f3917);
        

        marker_b3a1965cac1b131dfd1fbcb3b6a4dae6.bindPopup(popup_31c3d7a3d90571bde938e069c6a67157)
        ;

        
    
    
            var marker_175d20fc89f0a482a92b10c6652ebf70 = L.marker(
                [55.682461, 12.576892],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_f23020e843f032a9180cbb22037d3b73 = L.popup({"maxWidth": "100%"});

        
            var html_435e80cc918dd2a6e1cc84cface8bbc9 = $(`<div id="html_435e80cc918dd2a6e1cc84cface8bbc9" style="width: 100.0%; height: 100.0%;">Year Built: 1965, Price:25.000.000, 238.0 m2 , ZipCode:1119 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_f23020e843f032a9180cbb22037d3b73.setContent(html_435e80cc918dd2a6e1cc84cface8bbc9);
        

        marker_175d20fc89f0a482a92b10c6652ebf70.bindPopup(popup_f23020e843f032a9180cbb22037d3b73)
        ;

        
    
    
            var marker_77a996e364b2458c1789bcc69679d67a = L.marker(
                [55.685723, 12.568696],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_6a1a1ea9d352aa70993b55014aaa1c87 = L.popup({"maxWidth": "100%"});

        
            var html_3da78d1635201906acf179ff4ec71317 = $(`<div id="html_3da78d1635201906acf179ff4ec71317" style="width: 100.0%; height: 100.0%;">Year Built: 1877, Price:8.750.000, 150.0 m2 , ZipCode:1123 ,  Rooms:5, HomeType:Ejerlejlighed</div>`)[0];
            popup_6a1a1ea9d352aa70993b55014aaa1c87.setContent(html_3da78d1635201906acf179ff4ec71317);
        

        marker_77a996e364b2458c1789bcc69679d67a.bindPopup(popup_6a1a1ea9d352aa70993b55014aaa1c87)
        ;

        
    
    
            var marker_95b38dbc8ad1446202d97a3649b84cc0 = L.marker(
                [55.683466, 12.577321],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_58f246ac89c53a17111811d095e4a5d6 = L.popup({"maxWidth": "100%"});

        
            var html_542744f4c5dc7d9190b667e646b5b9f7 = $(`<div id="html_542744f4c5dc7d9190b667e646b5b9f7" style="width: 100.0%; height: 100.0%;">Year Built: 1883, Price:6.195.000, 99.0 m2 , ZipCode:1123 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_58f246ac89c53a17111811d095e4a5d6.setContent(html_542744f4c5dc7d9190b667e646b5b9f7);
        

        marker_95b38dbc8ad1446202d97a3649b84cc0.bindPopup(popup_58f246ac89c53a17111811d095e4a5d6)
        ;

        
    
    
            var marker_3d02c492d700b1ba463fa907f1af928f = L.marker(
                [55.68311, 12.575676],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_faec2a32c2d8a419158b9ef71c6082b6 = L.popup({"maxWidth": "100%"});

        
            var html_da7cb442ac92bfc0c4063368585671e9 = $(`<div id="html_da7cb442ac92bfc0c4063368585671e9" style="width: 100.0%; height: 100.0%;">Year Built: 1854, Price:3.395.000, 49.0 m2 , ZipCode:1127 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_faec2a32c2d8a419158b9ef71c6082b6.setContent(html_da7cb442ac92bfc0c4063368585671e9);
        

        marker_3d02c492d700b1ba463fa907f1af928f.bindPopup(popup_faec2a32c2d8a419158b9ef71c6082b6)
        ;

        
    
    
            var marker_fdf28154a8e7e7d4f31497d5558c7499 = L.marker(
                [55.679982, 12.57784],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_3e11196ce0f4b8685db35269c8585a15 = L.popup({"maxWidth": "100%"});

        
            var html_ae509b1b28953510bd2d0accf93e2ba9 = $(`<div id="html_ae509b1b28953510bd2d0accf93e2ba9" style="width: 100.0%; height: 100.0%;">Year Built: 1853, Price:4.695.000, 76.0 m2 , ZipCode:1151 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_3e11196ce0f4b8685db35269c8585a15.setContent(html_ae509b1b28953510bd2d0accf93e2ba9);
        

        marker_fdf28154a8e7e7d4f31497d5558c7499.bindPopup(popup_3e11196ce0f4b8685db35269c8585a15)
        ;

        
    
    
            var marker_f29f5c79b73fdc0412c0d02271df7d8c = L.marker(
                [55.680037, 12.578078],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_d0876f18345e233753350e55493d5940 = L.popup({"maxWidth": "100%"});

        
            var html_128ca8082fd743229d7cae0014c300b6 = $(`<div id="html_128ca8082fd743229d7cae0014c300b6" style="width: 100.0%; height: 100.0%;">Year Built: 1853, Price:5.300.000, 84.0 m2 , ZipCode:1151 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_d0876f18345e233753350e55493d5940.setContent(html_128ca8082fd743229d7cae0014c300b6);
        

        marker_f29f5c79b73fdc0412c0d02271df7d8c.bindPopup(popup_d0876f18345e233753350e55493d5940)
        ;

        
    
    
            var marker_502b8afa0d222bf3e3dc528de2ebcd4b = L.marker(
                [55.679982, 12.57784],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_7cb4c1480f2ba3284b91471b48f39cc2 = L.popup({"maxWidth": "100%"});

        
            var html_9c893d299189eb1fe1c483c93ed1eb2c = $(`<div id="html_9c893d299189eb1fe1c483c93ed1eb2c" style="width: 100.0%; height: 100.0%;">Year Built: 1853, Price:4.198.000, 58.0 m2 , ZipCode:1151 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_7cb4c1480f2ba3284b91471b48f39cc2.setContent(html_9c893d299189eb1fe1c483c93ed1eb2c);
        

        marker_502b8afa0d222bf3e3dc528de2ebcd4b.bindPopup(popup_7cb4c1480f2ba3284b91471b48f39cc2)
        ;

        
    
    
            var marker_dc4ca3fdabbf4c83b31cdbf5a4a3e292 = L.marker(
                [55.679401, 12.575264],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_77b05c94c726339a19eb413dd5f21fde = L.popup({"maxWidth": "100%"});

        
            var html_ce52536d65152797cd0139083a9eb69d = $(`<div id="html_ce52536d65152797cd0139083a9eb69d" style="width: 100.0%; height: 100.0%;">Year Built: 1813, Price:6.495.000, 84.0 m2 , ZipCode:1156 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_77b05c94c726339a19eb413dd5f21fde.setContent(html_ce52536d65152797cd0139083a9eb69d);
        

        marker_dc4ca3fdabbf4c83b31cdbf5a4a3e292.bindPopup(popup_77b05c94c726339a19eb413dd5f21fde)
        ;

        
    
    
            var marker_f63f59a51917342cdf5f309251c0d315 = L.marker(
                [55.679625, 12.574807],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_589b2200a9a5cf07c48a565de20b8b83 = L.popup({"maxWidth": "100%"});

        
            var html_d7d46f1a185f90eb4adeb10002ce592a = $(`<div id="html_d7d46f1a185f90eb4adeb10002ce592a" style="width: 100.0%; height: 100.0%;">Year Built: 1821, Price:5.198.000, 80.0 m2 , ZipCode:1157 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_589b2200a9a5cf07c48a565de20b8b83.setContent(html_d7d46f1a185f90eb4adeb10002ce592a);
        

        marker_f63f59a51917342cdf5f309251c0d315.bindPopup(popup_589b2200a9a5cf07c48a565de20b8b83)
        ;

        
    
    
            var marker_581ca10d8085a9f1d6a0f05b40cae7e9 = L.marker(
                [55.679514, 12.574983],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_cf08ad3ab89f791eca75fa74b35ef3c4 = L.popup({"maxWidth": "100%"});

        
            var html_64069337f2d2abe9e821661fcba2a86a = $(`<div id="html_64069337f2d2abe9e821661fcba2a86a" style="width: 100.0%; height: 100.0%;">Year Built: 1820, Price:4.695.000, 86.0 m2 , ZipCode:1157 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_cf08ad3ab89f791eca75fa74b35ef3c4.setContent(html_64069337f2d2abe9e821661fcba2a86a);
        

        marker_581ca10d8085a9f1d6a0f05b40cae7e9.bindPopup(popup_cf08ad3ab89f791eca75fa74b35ef3c4)
        ;

        
    
    
            var marker_3ae50a5aa997578a02bf3fb285bbf1fd = L.marker(
                [55.679352, 12.574053],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_5fdce879636d0b74ead0119eff67cf24 = L.popup({"maxWidth": "100%"});

        
            var html_23deb8c1140b8ce93c677ddb7fe83d79 = $(`<div id="html_23deb8c1140b8ce93c677ddb7fe83d79" style="width: 100.0%; height: 100.0%;">Year Built: 1838, Price:8.995.000, 200.0 m2 , ZipCode:1159 ,  Rooms:6, HomeType:Ejerlejlighed</div>`)[0];
            popup_5fdce879636d0b74ead0119eff67cf24.setContent(html_23deb8c1140b8ce93c677ddb7fe83d79);
        

        marker_3ae50a5aa997578a02bf3fb285bbf1fd.bindPopup(popup_5fdce879636d0b74ead0119eff67cf24)
        ;

        
    
    
            var marker_fb9b0e7f3eb887635b82fb7c0bdf5f5b = L.marker(
                [55.6791188, 12.5739092],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_bdae8e8e1899c9957667ed4818c95240 = L.popup({"maxWidth": "100%"});

        
            var html_a0a1f6a38fd0797a22aac4ac5d0d84d6 = $(`<div id="html_a0a1f6a38fd0797a22aac4ac5d0d84d6" style="width: 100.0%; height: 100.0%;">Year Built: 1830, Price:5.500.000, 120.0 m2 , ZipCode:1159 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_bdae8e8e1899c9957667ed4818c95240.setContent(html_a0a1f6a38fd0797a22aac4ac5d0d84d6);
        

        marker_fb9b0e7f3eb887635b82fb7c0bdf5f5b.bindPopup(popup_bdae8e8e1899c9957667ed4818c95240)
        ;

        
    
    
            var marker_151886b1f50fe6f1fdad7788c6b960c1 = L.marker(
                [55.681742, 12.570712],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_9df2dd894b7b52246b2d411c7dd2b40b = L.popup({"maxWidth": "100%"});

        
            var html_033ee8ca4be03e62932646bee89bed7c = $(`<div id="html_033ee8ca4be03e62932646bee89bed7c" style="width: 100.0%; height: 100.0%;">Year Built: 1810, Price:4.295.000, 87.0 m2 , ZipCode:1165 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_9df2dd894b7b52246b2d411c7dd2b40b.setContent(html_033ee8ca4be03e62932646bee89bed7c);
        

        marker_151886b1f50fe6f1fdad7788c6b960c1.bindPopup(popup_9df2dd894b7b52246b2d411c7dd2b40b)
        ;

        
    
    
            var marker_cf953a63ce53f3f0941b427baeeecd98 = L.marker(
                [55.680381, 12.57463],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_3bbb941fde2d7ec4fb2b1c6c02fc1206 = L.popup({"maxWidth": "100%"});

        
            var html_245d13a9c6cb80a1b168a7624e881f3b = $(`<div id="html_245d13a9c6cb80a1b168a7624e881f3b" style="width: 100.0%; height: 100.0%;">Year Built: 1829, Price:6.995.000, 100.0 m2 , ZipCode:1169 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_3bbb941fde2d7ec4fb2b1c6c02fc1206.setContent(html_245d13a9c6cb80a1b168a7624e881f3b);
        

        marker_cf953a63ce53f3f0941b427baeeecd98.bindPopup(popup_3bbb941fde2d7ec4fb2b1c6c02fc1206)
        ;

        
    
    
            var marker_2be143a76204e3ccce570f587438a336 = L.marker(
                [55.681645, 12.572494],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_aaccee4e8db2e5d626605b568a1c4979 = L.popup({"maxWidth": "100%"});

        
            var html_f740b0cf74adaf999f0935340f08ba1d = $(`<div id="html_f740b0cf74adaf999f0935340f08ba1d" style="width: 100.0%; height: 100.0%;">Year Built: 1809, Price:5.450.000, 73.0 m2 , ZipCode:1171 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_aaccee4e8db2e5d626605b568a1c4979.setContent(html_f740b0cf74adaf999f0935340f08ba1d);
        

        marker_2be143a76204e3ccce570f587438a336.bindPopup(popup_aaccee4e8db2e5d626605b568a1c4979)
        ;

        
    
    
            var marker_0656312c896a667819483bdc1ec6278a = L.marker(
                [55.677767, 12.578537],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_dc19cd8159408b97a5c8c7ed438381f9 = L.popup({"maxWidth": "100%"});

        
            var html_00ee73b0221a3a8fd955a08e1013adda = $(`<div id="html_00ee73b0221a3a8fd955a08e1013adda" style="width: 100.0%; height: 100.0%;">Year Built: 1798, Price:11.495.000, 153.0 m2 , ZipCode:1202 ,  Rooms:6, HomeType:Ejerlejlighed</div>`)[0];
            popup_dc19cd8159408b97a5c8c7ed438381f9.setContent(html_00ee73b0221a3a8fd955a08e1013adda);
        

        marker_0656312c896a667819483bdc1ec6278a.bindPopup(popup_dc19cd8159408b97a5c8c7ed438381f9)
        ;

        
    
    
            var marker_f1619e65a7aab926e8208979864380ac = L.marker(
                [55.676208, 12.575167],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_3954a7744c18de1a53903ff349fa931e = L.popup({"maxWidth": "100%"});

        
            var html_ad7f2ac575ab91f78bb29f1864781c07 = $(`<div id="html_ad7f2ac575ab91f78bb29f1864781c07" style="width: 100.0%; height: 100.0%;">Year Built: 1650, Price:3.695.000, 58.0 m2 , ZipCode:1204 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_3954a7744c18de1a53903ff349fa931e.setContent(html_ad7f2ac575ab91f78bb29f1864781c07);
        

        marker_f1619e65a7aab926e8208979864380ac.bindPopup(popup_3954a7744c18de1a53903ff349fa931e)
        ;

        
    
    
            var marker_70f4bb48c1734b92b572ba047403f4bf = L.marker(
                [55.676265, 12.574971],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_82df35ed1f1d6f4b617d44fb2ec18f80 = L.popup({"maxWidth": "100%"});

        
            var html_6ae80d12ddf505e09db21d02a5e26555 = $(`<div id="html_6ae80d12ddf505e09db21d02a5e26555" style="width: 100.0%; height: 100.0%;">Year Built: 1700, Price:6.995.000, 147.0 m2 , ZipCode:1204 ,  Rooms:6, HomeType:Ejerlejlighed</div>`)[0];
            popup_82df35ed1f1d6f4b617d44fb2ec18f80.setContent(html_6ae80d12ddf505e09db21d02a5e26555);
        

        marker_70f4bb48c1734b92b572ba047403f4bf.bindPopup(popup_82df35ed1f1d6f4b617d44fb2ec18f80)
        ;

        
    
    
            var marker_3f71ed34ea597482b7a9183bed540ebd = L.marker(
                [55.677628, 12.576342],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_a461759b19a068076d63709710c69cc0 = L.popup({"maxWidth": "100%"});

        
            var html_60f76405f4c120d1522d5ba05bd898ad = $(`<div id="html_60f76405f4c120d1522d5ba05bd898ad" style="width: 100.0%; height: 100.0%;">Year Built: 1800, Price:6.495.000, 109.0 m2 , ZipCode:1208 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_a461759b19a068076d63709710c69cc0.setContent(html_60f76405f4c120d1522d5ba05bd898ad);
        

        marker_3f71ed34ea597482b7a9183bed540ebd.bindPopup(popup_a461759b19a068076d63709710c69cc0)
        ;

        
    
    
            var marker_4b1c6ec6af417e9067fe03dd51744c12 = L.marker(
                [55.67757, 12.575426],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_c490a23d3d4900a9efd79afe1538d6e3 = L.popup({"maxWidth": "100%"});

        
            var html_65aefee8cd3144ff93f68a0870092f18 = $(`<div id="html_65aefee8cd3144ff93f68a0870092f18" style="width: 100.0%; height: 100.0%;">Year Built: 1790, Price:6.998.000, 111.0 m2 , ZipCode:1209 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_c490a23d3d4900a9efd79afe1538d6e3.setContent(html_65aefee8cd3144ff93f68a0870092f18);
        

        marker_4b1c6ec6af417e9067fe03dd51744c12.bindPopup(popup_c490a23d3d4900a9efd79afe1538d6e3)
        ;

        
    
    
            var marker_c800941d5d4110b3725a48368663a8f7 = L.marker(
                [55.676956, 12.575842],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_d6f396bda618e24e21bce9698b214070 = L.popup({"maxWidth": "100%"});

        
            var html_b21e9d263fd3c7acad870dd88c4ec253 = $(`<div id="html_b21e9d263fd3c7acad870dd88c4ec253" style="width: 100.0%; height: 100.0%;">Year Built: 1798, Price:3.500.000, 49.0 m2 , ZipCode:1210 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_d6f396bda618e24e21bce9698b214070.setContent(html_b21e9d263fd3c7acad870dd88c4ec253);
        

        marker_c800941d5d4110b3725a48368663a8f7.bindPopup(popup_d6f396bda618e24e21bce9698b214070)
        ;

        
    
    
            var marker_bec88c351ba1ab6ad9cf84574b66f8cc = L.marker(
                [55.677324, 12.574169],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_74d6b086e5ba3b61721bc60d47b6dcac = L.popup({"maxWidth": "100%"});

        
            var html_8ef965bbb31c2a03ea71513d58f689f2 = $(`<div id="html_8ef965bbb31c2a03ea71513d58f689f2" style="width: 100.0%; height: 100.0%;">Year Built: 1798, Price:6.995.000, 115.0 m2 , ZipCode:1211 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_74d6b086e5ba3b61721bc60d47b6dcac.setContent(html_8ef965bbb31c2a03ea71513d58f689f2);
        

        marker_bec88c351ba1ab6ad9cf84574b66f8cc.bindPopup(popup_74d6b086e5ba3b61721bc60d47b6dcac)
        ;

        
    
    
            var marker_29b2595346c75d64e38d5ad685ff8101 = L.marker(
                [55.683038, 12.591639],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_c699b75fd598fc5246e3d21aeaf97528 = L.popup({"maxWidth": "100%"});

        
            var html_4fb83236c098552b8dde0f752cc78ada = $(`<div id="html_4fb83236c098552b8dde0f752cc78ada" style="width: 100.0%; height: 100.0%;">Year Built: 1962, Price:3.995.000, 57.0 m2 , ZipCode:1256 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_c699b75fd598fc5246e3d21aeaf97528.setContent(html_4fb83236c098552b8dde0f752cc78ada);
        

        marker_29b2595346c75d64e38d5ad685ff8101.bindPopup(popup_c699b75fd598fc5246e3d21aeaf97528)
        ;

        
    
    
            var marker_4398c190704f9a6405f88b0529c3aee6 = L.marker(
                [55.681953, 12.588488],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_f4e62f44de603f095e16f97aff6c16c5 = L.popup({"maxWidth": "100%"});

        
            var html_3cd1608a50752623b01526436c1d1eef = $(`<div id="html_3cd1608a50752623b01526436c1d1eef" style="width: 100.0%; height: 100.0%;">Year Built: 1806, Price:7.495.000, 99.0 m2 , ZipCode:1260 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_f4e62f44de603f095e16f97aff6c16c5.setContent(html_3cd1608a50752623b01526436c1d1eef);
        

        marker_4398c190704f9a6405f88b0529c3aee6.bindPopup(popup_f4e62f44de603f095e16f97aff6c16c5)
        ;

        
    
    
            var marker_a2b3d3baa42f046b109527455896b1ea = L.marker(
                [55.686572, 12.589835],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_7a0a14ff293b4599d14a2f1ae19b96e6 = L.popup({"maxWidth": "100%"});

        
            var html_45dae778463deade33a9ffbe388f19fa = $(`<div id="html_45dae778463deade33a9ffbe388f19fa" style="width: 100.0%; height: 100.0%;">Year Built: 1866, Price:6.695.000, 97.0 m2 , ZipCode:1264 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_7a0a14ff293b4599d14a2f1ae19b96e6.setContent(html_45dae778463deade33a9ffbe388f19fa);
        

        marker_a2b3d3baa42f046b109527455896b1ea.bindPopup(popup_7a0a14ff293b4599d14a2f1ae19b96e6)
        ;

        
    
    
            var marker_90f0aecc912072e27d2db36816c7cfc2 = L.marker(
                [55.685701, 12.589098],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_6a7f8e4abdba86b836e52a7666f3c180 = L.popup({"maxWidth": "100%"});

        
            var html_a50685c8dfdf18ac7972293367f2a65b = $(`<div id="html_a50685c8dfdf18ac7972293367f2a65b" style="width: 100.0%; height: 100.0%;">Year Built: 1880, Price:11.245.000, 142.0 m2 , ZipCode:1264 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_6a7f8e4abdba86b836e52a7666f3c180.setContent(html_a50685c8dfdf18ac7972293367f2a65b);
        

        marker_90f0aecc912072e27d2db36816c7cfc2.bindPopup(popup_6a7f8e4abdba86b836e52a7666f3c180)
        ;

        
    
    
            var marker_e8ca7c1e51b900e3825ec8f0c5a23cb9 = L.marker(
                [55.684572, 12.589263],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_44566512fe4b9ba2314975a55ebdef6b = L.popup({"maxWidth": "100%"});

        
            var html_01be360f430a1c3a3938e156ff12a6d9 = $(`<div id="html_01be360f430a1c3a3938e156ff12a6d9" style="width: 100.0%; height: 100.0%;">Year Built: 1885, Price:9.500.000, 127.0 m2 , ZipCode:1265 ,  Rooms:5, HomeType:Ejerlejlighed</div>`)[0];
            popup_44566512fe4b9ba2314975a55ebdef6b.setContent(html_01be360f430a1c3a3938e156ff12a6d9);
        

        marker_e8ca7c1e51b900e3825ec8f0c5a23cb9.bindPopup(popup_44566512fe4b9ba2314975a55ebdef6b)
        ;

        
    
    
            var marker_4051a47529bc74581c64cfb34bb050ac = L.marker(
                [55.688514, 12.590586],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_df97cc86b3b97b45c68add90d167fbf6 = L.popup({"maxWidth": "100%"});

        
            var html_468f066e1511a966e8a4c8a65148ffa7 = $(`<div id="html_468f066e1511a966e8a4c8a65148ffa7" style="width: 100.0%; height: 100.0%;">Year Built: 1925, Price:14.995.000, 226.0 m2 , ZipCode:1267 ,  Rooms:6, HomeType:Ejerlejlighed</div>`)[0];
            popup_df97cc86b3b97b45c68add90d167fbf6.setContent(html_468f066e1511a966e8a4c8a65148ffa7);
        

        marker_4051a47529bc74581c64cfb34bb050ac.bindPopup(popup_df97cc86b3b97b45c68add90d167fbf6)
        ;

        
    
    
            var marker_6b97a20034919a49423cbc8c393e8f88 = L.marker(
                [55.684913, 12.584743],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_67316307aa1240b50ccba4ec6e99ea86 = L.popup({"maxWidth": "100%"});

        
            var html_f4ee82d1f059661ff18bee68d2b2b95d = $(`<div id="html_f4ee82d1f059661ff18bee68d2b2b95d" style="width: 100.0%; height: 100.0%;">Year Built: 1957, Price:4.195.000, 56.0 m2 , ZipCode:1302 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_67316307aa1240b50ccba4ec6e99ea86.setContent(html_f4ee82d1f059661ff18bee68d2b2b95d);
        

        marker_6b97a20034919a49423cbc8c393e8f88.bindPopup(popup_67316307aa1240b50ccba4ec6e99ea86)
        ;

        
    
    
            var marker_de65daad0b18d383a58ff431672c5545 = L.marker(
                [55.684729, 12.585416],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_65500be2901e398ef9580f8d49ec0f3b = L.popup({"maxWidth": "100%"});

        
            var html_ed531b525fbc9b4f06c23fd57a81f950 = $(`<div id="html_ed531b525fbc9b4f06c23fd57a81f950" style="width: 100.0%; height: 100.0%;">Year Built: 1957, Price:2.745.000, 43.0 m2 , ZipCode:1302 ,  Rooms:1, HomeType:Ejerlejlighed</div>`)[0];
            popup_65500be2901e398ef9580f8d49ec0f3b.setContent(html_ed531b525fbc9b4f06c23fd57a81f950);
        

        marker_de65daad0b18d383a58ff431672c5545.bindPopup(popup_65500be2901e398ef9580f8d49ec0f3b)
        ;

        
    
    
            var marker_f0dcaf9c9c20929b2b3f7580604ef41d = L.marker(
                [55.684913, 12.584743],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_e5a8d910d09e82e017084eb1cf55f275 = L.popup({"maxWidth": "100%"});

        
            var html_f7e9b2989ee2792527bc82ead6a06764 = $(`<div id="html_f7e9b2989ee2792527bc82ead6a06764" style="width: 100.0%; height: 100.0%;">Year Built: 1957, Price:3.800.000, 59.0 m2 , ZipCode:1302 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_e5a8d910d09e82e017084eb1cf55f275.setContent(html_f7e9b2989ee2792527bc82ead6a06764);
        

        marker_f0dcaf9c9c20929b2b3f7580604ef41d.bindPopup(popup_e5a8d910d09e82e017084eb1cf55f275)
        ;

        
    
    
            var marker_6d5fac23234fba11fb116c4d958f20f5 = L.marker(
                [55.683703, 12.58788],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_32175324046dfb9de9145116b19c2db1 = L.popup({"maxWidth": "100%"});

        
            var html_51d9f1232cbf63fc9431ec8f54ae3585 = $(`<div id="html_51d9f1232cbf63fc9431ec8f54ae3585" style="width: 100.0%; height: 100.0%;">Year Built: 1780, Price:5.450.000, 61.0 m2 , ZipCode:1302 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_32175324046dfb9de9145116b19c2db1.setContent(html_51d9f1232cbf63fc9431ec8f54ae3585);
        

        marker_6d5fac23234fba11fb116c4d958f20f5.bindPopup(popup_32175324046dfb9de9145116b19c2db1)
        ;

        
    
    
            var marker_269d6d2a142cec4b91d168d78984e11b = L.marker(
                [55.684858, 12.584943],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_210ecf4ed0334f178c9dc66f9dee9128 = L.popup({"maxWidth": "100%"});

        
            var html_7e4baca55b89731883099dab7ab31291 = $(`<div id="html_7e4baca55b89731883099dab7ab31291" style="width: 100.0%; height: 100.0%;">Year Built: 1957, Price:5.495.000, 83.0 m2 , ZipCode:1302 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_210ecf4ed0334f178c9dc66f9dee9128.setContent(html_7e4baca55b89731883099dab7ab31291);
        

        marker_269d6d2a142cec4b91d168d78984e11b.bindPopup(popup_210ecf4ed0334f178c9dc66f9dee9128)
        ;

        
    
    
            var marker_cf1bb025233291825a9941ffb22cd2c2 = L.marker(
                [55.684729, 12.585416],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_9f97a729a5be0f4dfa76c02b5b1f76aa = L.popup({"maxWidth": "100%"});

        
            var html_d3f822426f5d1b9410af440a815e2ffc = $(`<div id="html_d3f822426f5d1b9410af440a815e2ffc" style="width: 100.0%; height: 100.0%;">Year Built: 1957, Price:5.295.000, 82.0 m2 , ZipCode:1302 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_9f97a729a5be0f4dfa76c02b5b1f76aa.setContent(html_d3f822426f5d1b9410af440a815e2ffc);
        

        marker_cf1bb025233291825a9941ffb22cd2c2.bindPopup(popup_9f97a729a5be0f4dfa76c02b5b1f76aa)
        ;

        
    
    
            var marker_bd61d5e1ef6818ef4f7e70bbb571c353 = L.marker(
                [55.685932, 12.588164],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_f2580acacfd354f6858dc5964c081388 = L.popup({"maxWidth": "100%"});

        
            var html_10b0b7d74114464af6a1f6e0fe4d1b6b = $(`<div id="html_10b0b7d74114464af6a1f6e0fe4d1b6b" style="width: 100.0%; height: 100.0%;">Year Built: 1901, Price:7.750.000, 103.0 m2 , ZipCode:1303 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_f2580acacfd354f6858dc5964c081388.setContent(html_10b0b7d74114464af6a1f6e0fe4d1b6b);
        

        marker_bd61d5e1ef6818ef4f7e70bbb571c353.bindPopup(popup_f2580acacfd354f6858dc5964c081388)
        ;

        
    
    
            var marker_25860f055247af618a0b18901a764311 = L.marker(
                [55.685782, 12.583877],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_a30158c34e1a8c3a27d8d579f5025568 = L.popup({"maxWidth": "100%"});

        
            var html_4e7a7a019748a329cee9f632fd5bcaab = $(`<div id="html_4e7a7a019748a329cee9f632fd5bcaab" style="width: 100.0%; height: 100.0%;">Year Built: 1806, Price:4.495.000, 76.0 m2 , ZipCode:1307 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_a30158c34e1a8c3a27d8d579f5025568.setContent(html_4e7a7a019748a329cee9f632fd5bcaab);
        

        marker_25860f055247af618a0b18901a764311.bindPopup(popup_a30158c34e1a8c3a27d8d579f5025568)
        ;

        
    
    
            var marker_50ea7791ae1966ea9b2f9d630482dd63 = L.marker(
                [55.685842, 12.583649],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_49d8ce20cc166f4b663000df178ee8fa = L.popup({"maxWidth": "100%"});

        
            var html_f9ac4463368794300263facceaacd213 = $(`<div id="html_f9ac4463368794300263facceaacd213" style="width: 100.0%; height: 100.0%;">Year Built: 1806, Price:3.995.000, 64.0 m2 , ZipCode:1307 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_49d8ce20cc166f4b663000df178ee8fa.setContent(html_f9ac4463368794300263facceaacd213);
        

        marker_50ea7791ae1966ea9b2f9d630482dd63.bindPopup(popup_49d8ce20cc166f4b663000df178ee8fa)
        ;

        
    
    
            var marker_1827c445a62c9c6fd9139007654b19d0 = L.marker(
                [55.685614, 12.584512],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_bb91fe324ed82e4bbdb53d6d1f0ddea7 = L.popup({"maxWidth": "100%"});

        
            var html_b62c97bea04684c0b3becd1c244f7541 = $(`<div id="html_b62c97bea04684c0b3becd1c244f7541" style="width: 100.0%; height: 100.0%;">Year Built: 1957, Price:3.275.000, 52.0 m2 , ZipCode:1307 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_bb91fe324ed82e4bbdb53d6d1f0ddea7.setContent(html_b62c97bea04684c0b3becd1c244f7541);
        

        marker_1827c445a62c9c6fd9139007654b19d0.bindPopup(popup_bb91fe324ed82e4bbdb53d6d1f0ddea7)
        ;

        
    
    
            var marker_2602a1546c71b7022bdce7f86cbef19b = L.marker(
                [55.685614, 12.584512],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_2f82d649484b734008e0251be90b0e39 = L.popup({"maxWidth": "100%"});

        
            var html_9bfa52d5c753928101ca7ccd39f608fd = $(`<div id="html_9bfa52d5c753928101ca7ccd39f608fd" style="width: 100.0%; height: 100.0%;">Year Built: 1957, Price:3.495.000, 52.0 m2 , ZipCode:1307 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_2f82d649484b734008e0251be90b0e39.setContent(html_9bfa52d5c753928101ca7ccd39f608fd);
        

        marker_2602a1546c71b7022bdce7f86cbef19b.bindPopup(popup_2f82d649484b734008e0251be90b0e39)
        ;

        
    
    
            var marker_1d0f25981ab73d2bda813f357e61f572 = L.marker(
                [55.68978, 12.573885],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_6ba0f558ca2bce8e371a5ae0e9e4f665 = L.popup({"maxWidth": "100%"});

        
            var html_9c598147ebddd2fa56a9d2a4e7e16eb4 = $(`<div id="html_9c598147ebddd2fa56a9d2a4e7e16eb4" style="width: 100.0%; height: 100.0%;">Year Built: 1882, Price:4.100.000, 72.0 m2 , ZipCode:1307 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_6ba0f558ca2bce8e371a5ae0e9e4f665.setContent(html_9c598147ebddd2fa56a9d2a4e7e16eb4);
        

        marker_1d0f25981ab73d2bda813f357e61f572.bindPopup(popup_6ba0f558ca2bce8e371a5ae0e9e4f665)
        ;

        
    
    
            var marker_b6c63aa2fa7a7534333d9403006566ca = L.marker(
                [55.686457, 12.584771],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_0f8d5e5fc35517b6254677807c580b0a = L.popup({"maxWidth": "100%"});

        
            var html_95a0112c384d512a9e44a8f65808f317 = $(`<div id="html_95a0112c384d512a9e44a8f65808f317" style="width: 100.0%; height: 100.0%;">Year Built: 1810, Price:3.500.000, 46.0 m2 , ZipCode:1308 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_0f8d5e5fc35517b6254677807c580b0a.setContent(html_95a0112c384d512a9e44a8f65808f317);
        

        marker_b6c63aa2fa7a7534333d9403006566ca.bindPopup(popup_0f8d5e5fc35517b6254677807c580b0a)
        ;

        
    
    
            var marker_7319c66064a27c5948dab01611b258e6 = L.marker(
                [55.686501, 12.58533],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_cf06a844cab0d9d12f13996ef366b10d = L.popup({"maxWidth": "100%"});

        
            var html_e31b1c2dcaf6b1c8392f0e5fe2e711b6 = $(`<div id="html_e31b1c2dcaf6b1c8392f0e5fe2e711b6" style="width: 100.0%; height: 100.0%;">Year Built: 1888, Price:5.750.000, 98.0 m2 , ZipCode:1308 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_cf06a844cab0d9d12f13996ef366b10d.setContent(html_e31b1c2dcaf6b1c8392f0e5fe2e711b6);
        

        marker_7319c66064a27c5948dab01611b258e6.bindPopup(popup_cf06a844cab0d9d12f13996ef366b10d)
        ;

        
    
    
            var marker_b031c59fbd14a4068ecd6469a73b9a4d = L.marker(
                [55.685658, 12.590515],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_2986de31060cac9ea37b5f99d186b3c7 = L.popup({"maxWidth": "100%"});

        
            var html_c55820a39e2311957b15fc49a8070985 = $(`<div id="html_c55820a39e2311957b15fc49a8070985" style="width: 100.0%; height: 100.0%;">Year Built: 2007, Price:9.795.000, 140.0 m2 , ZipCode:1310 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_2986de31060cac9ea37b5f99d186b3c7.setContent(html_c55820a39e2311957b15fc49a8070985);
        

        marker_b031c59fbd14a4068ecd6469a73b9a4d.bindPopup(popup_2986de31060cac9ea37b5f99d186b3c7)
        ;

        
    
    
            var marker_a55212daf9b3b9188b5295072907fc79 = L.marker(
                [55.686979, 12.582069],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_b11c9331def02c084a0599cb1db87d0e = L.popup({"maxWidth": "100%"});

        
            var html_ff746fcd8993174331c3d34569751ef7 = $(`<div id="html_ff746fcd8993174331c3d34569751ef7" style="width: 100.0%; height: 100.0%;">Year Built: 1759, Price:8.995.000, 93.0 m2 , ZipCode:1316 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_b11c9331def02c084a0599cb1db87d0e.setContent(html_ff746fcd8993174331c3d34569751ef7);
        

        marker_a55212daf9b3b9188b5295072907fc79.bindPopup(popup_b11c9331def02c084a0599cb1db87d0e)
        ;

        
    
    
            var marker_70e22a04e2146e8d864655d4197e6b25 = L.marker(
                [55.689738, 12.584051],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_33705368ff93aa851c6e1aa6edd0d60c = L.popup({"maxWidth": "100%"});

        
            var html_07b40f4bf1c1eec677b710deca15cbde = $(`<div id="html_07b40f4bf1c1eec677b710deca15cbde" style="width: 100.0%; height: 100.0%;">Year Built: 1800, Price:3.495.000, 63.0 m2 , ZipCode:1350 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_33705368ff93aa851c6e1aa6edd0d60c.setContent(html_07b40f4bf1c1eec677b710deca15cbde);
        

        marker_70e22a04e2146e8d864655d4197e6b25.bindPopup(popup_33705368ff93aa851c6e1aa6edd0d60c)
        ;

        
    
    
            var marker_d09896166539c86d5609df37068ca1f9 = L.marker(
                [55.690203, 12.571643],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_f707e4641d9211b657bb4063624a639e = L.popup({"maxWidth": "100%"});

        
            var html_18aa7269844dc0df7d89e2cbbc669de0 = $(`<div id="html_18aa7269844dc0df7d89e2cbbc669de0" style="width: 100.0%; height: 100.0%;">Year Built: 1884, Price:6.495.000, 104.0 m2 , ZipCode:1352 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_f707e4641d9211b657bb4063624a639e.setContent(html_18aa7269844dc0df7d89e2cbbc669de0);
        

        marker_d09896166539c86d5609df37068ca1f9.bindPopup(popup_f707e4641d9211b657bb4063624a639e)
        ;

        
    
    
            var marker_3b15a2112b0c39e90b1ab706ab0e6db3 = L.marker(
                [55.689047, 12.571626],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_a0c5f41433d43bbec043b27f7557beb9 = L.popup({"maxWidth": "100%"});

        
            var html_a2368ca40158e59cf65e9c73965a27e6 = $(`<div id="html_a2368ca40158e59cf65e9c73965a27e6" style="width: 100.0%; height: 100.0%;">Year Built: 1884, Price:4.900.000, 82.0 m2 , ZipCode:1355 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_a0c5f41433d43bbec043b27f7557beb9.setContent(html_a2368ca40158e59cf65e9c73965a27e6);
        

        marker_3b15a2112b0c39e90b1ab706ab0e6db3.bindPopup(popup_a0c5f41433d43bbec043b27f7557beb9)
        ;

        
    
    
            var marker_96af65e8a4acda5000e0592536e21f58 = L.marker(
                [55.689829, 12.570473],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_1ca4e1455d4432ffb91215060fbd272d = L.popup({"maxWidth": "100%"});

        
            var html_9449071f8db1bca6c50340789e727e33 = $(`<div id="html_9449071f8db1bca6c50340789e727e33" style="width: 100.0%; height: 100.0%;">Year Built: 1883, Price:5.599.000, 83.0 m2 , ZipCode:1357 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_1ca4e1455d4432ffb91215060fbd272d.setContent(html_9449071f8db1bca6c50340789e727e33);
        

        marker_96af65e8a4acda5000e0592536e21f58.bindPopup(popup_1ca4e1455d4432ffb91215060fbd272d)
        ;

        
    
    
            var marker_bc8d11e6224dc5704732d443675e6363 = L.marker(
                [55.6882794, 12.5679843],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_96938b3585bcbc36a69f73858c786066 = L.popup({"maxWidth": "100%"});

        
            var html_edb1fb5369431b9e3ad4183f3cf93dfc = $(`<div id="html_edb1fb5369431b9e3ad4183f3cf93dfc" style="width: 100.0%; height: 100.0%;">Year Built: 1884, Price:11.995.000, 218.0 m2 , ZipCode:1357 ,  Rooms:6, HomeType:Ejerlejlighed</div>`)[0];
            popup_96938b3585bcbc36a69f73858c786066.setContent(html_edb1fb5369431b9e3ad4183f3cf93dfc);
        

        marker_bc8d11e6224dc5704732d443675e6363.bindPopup(popup_96938b3585bcbc36a69f73858c786066)
        ;

        
    
    
            var marker_748f1a9d186a4676b011d18630fc08f4 = L.marker(
                [55.690397, 12.571356],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_bce4ecf8bb6a6eec48b3ef84adff5003 = L.popup({"maxWidth": "100%"});

        
            var html_59063973fa5b07d0b044e40d3581e124 = $(`<div id="html_59063973fa5b07d0b044e40d3581e124" style="width: 100.0%; height: 100.0%;">Year Built: 1882, Price:5.995.000, 100.0 m2 , ZipCode:1357 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_bce4ecf8bb6a6eec48b3ef84adff5003.setContent(html_59063973fa5b07d0b044e40d3581e124);
        

        marker_748f1a9d186a4676b011d18630fc08f4.bindPopup(popup_bce4ecf8bb6a6eec48b3ef84adff5003)
        ;

        
    
    
            var marker_1703ae18ceb9c7a6b093acbdd248eba2 = L.marker(
                [55.685115, 12.567434],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_c167b6c922bfcc71a62e25ec5acc44bd = L.popup({"maxWidth": "100%"});

        
            var html_b87280894296ea04eaa432260d127d0f = $(`<div id="html_b87280894296ea04eaa432260d127d0f" style="width: 100.0%; height: 100.0%;">Year Built: 1876, Price:6.495.000, 158.0 m2 , ZipCode:1360 ,  Rooms:5, HomeType:Ejerlejlighed</div>`)[0];
            popup_c167b6c922bfcc71a62e25ec5acc44bd.setContent(html_b87280894296ea04eaa432260d127d0f);
        

        marker_1703ae18ceb9c7a6b093acbdd248eba2.bindPopup(popup_c167b6c922bfcc71a62e25ec5acc44bd)
        ;

        
    
    
            var marker_a3289887fea400dadf932debefdd91a0 = L.marker(
                [55.685005, 12.564938],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_0b9ad049051d7d88a3934aa9915a00b4 = L.popup({"maxWidth": "100%"});

        
            var html_01c261fe3ef5029baf3af02839380b84 = $(`<div id="html_01c261fe3ef5029baf3af02839380b84" style="width: 100.0%; height: 100.0%;">Year Built: 1880, Price:4.595.000, 70.0 m2 , ZipCode:1363 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_0b9ad049051d7d88a3934aa9915a00b4.setContent(html_01c261fe3ef5029baf3af02839380b84);
        

        marker_a3289887fea400dadf932debefdd91a0.bindPopup(popup_0b9ad049051d7d88a3934aa9915a00b4)
        ;

        
    
    
            var marker_309065347c2ccdb625df3d6dcab7256e = L.marker(
                [55.685082, 12.568743],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_65d517a02f72e074dadb8444bd8a4b86 = L.popup({"maxWidth": "100%"});

        
            var html_7f97561ea8cf0f9ec262a7f835259134 = $(`<div id="html_7f97561ea8cf0f9ec262a7f835259134" style="width: 100.0%; height: 100.0%;">Year Built: 1877, Price:9.875.000, 137.0 m2 , ZipCode:1364 ,  Rooms:5, HomeType:Ejerlejlighed</div>`)[0];
            popup_65d517a02f72e074dadb8444bd8a4b86.setContent(html_7f97561ea8cf0f9ec262a7f835259134);
        

        marker_309065347c2ccdb625df3d6dcab7256e.bindPopup(popup_65d517a02f72e074dadb8444bd8a4b86)
        ;

        
    
    
            var marker_a58093ecdbf8e9faf4559bcbf4369cfe = L.marker(
                [55.685584, 12.568732],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_74bb5a585ca4f7604f8fd96d588cb0eb = L.popup({"maxWidth": "100%"});

        
            var html_1bed0f0fb72fcfc627e3da200fac7181 = $(`<div id="html_1bed0f0fb72fcfc627e3da200fac7181" style="width: 100.0%; height: 100.0%;">Year Built: 1877, Price:5.995.000, 117.0 m2 , ZipCode:1364 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_74bb5a585ca4f7604f8fd96d588cb0eb.setContent(html_1bed0f0fb72fcfc627e3da200fac7181);
        

        marker_a58093ecdbf8e9faf4559bcbf4369cfe.bindPopup(popup_74bb5a585ca4f7604f8fd96d588cb0eb)
        ;

        
    
    
            var marker_bef7d10dac69c8937426b6fe79eeac3e = L.marker(
                [55.685122, 12.567232],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_12f417b7474737e96b2902aa4824c26d = L.popup({"maxWidth": "100%"});

        
            var html_2202082ec6bac0411fb6ef252a0034ac = $(`<div id="html_2202082ec6bac0411fb6ef252a0034ac" style="width: 100.0%; height: 100.0%;">Year Built: 1876, Price:5.395.000, 133.0 m2 , ZipCode:1366 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_12f417b7474737e96b2902aa4824c26d.setContent(html_2202082ec6bac0411fb6ef252a0034ac);
        

        marker_bef7d10dac69c8937426b6fe79eeac3e.bindPopup(popup_12f417b7474737e96b2902aa4824c26d)
        ;

        
    
    
            var marker_113d711262db8481e96e08109f364bcb = L.marker(
                [55.685122, 12.567232],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_fa85d97385bba245ea2090f4bf319bb1 = L.popup({"maxWidth": "100%"});

        
            var html_7cf79d0457ff90db39035e7aac7b3a00 = $(`<div id="html_7cf79d0457ff90db39035e7aac7b3a00" style="width: 100.0%; height: 100.0%;">Year Built: 1876, Price:5.495.000, 141.0 m2 , ZipCode:1366 ,  Rooms:5, HomeType:Ejerlejlighed</div>`)[0];
            popup_fa85d97385bba245ea2090f4bf319bb1.setContent(html_7cf79d0457ff90db39035e7aac7b3a00);
        

        marker_113d711262db8481e96e08109f364bcb.bindPopup(popup_fa85d97385bba245ea2090f4bf319bb1)
        ;

        
    
    
            var marker_e3be82466c8722df0ca093fb76b5b988 = L.marker(
                [55.681328, 12.563607],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_9199a0d6c8b3300ad0f2e6d84ddb8131 = L.popup({"maxWidth": "100%"});

        
            var html_26a1fe8df5095a70d0bac95e5ba3182b = $(`<div id="html_26a1fe8df5095a70d0bac95e5ba3182b" style="width: 100.0%; height: 100.0%;">Year Built: 1881, Price:3.895.000, 48.0 m2 , ZipCode:1368 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_9199a0d6c8b3300ad0f2e6d84ddb8131.setContent(html_26a1fe8df5095a70d0bac95e5ba3182b);
        

        marker_e3be82466c8722df0ca093fb76b5b988.bindPopup(popup_9199a0d6c8b3300ad0f2e6d84ddb8131)
        ;

        
    
    
            var marker_d571758a1630e7cf2604263e022d7751 = L.marker(
                [55.673575, 12.589553],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_5482695483a2cf3375fee9c6b3f655d5 = L.popup({"maxWidth": "100%"});

        
            var html_afb1303c4eb0867f0babd62f0436c36f = $(`<div id="html_afb1303c4eb0867f0babd62f0436c36f" style="width: 100.0%; height: 100.0%;">Year Built: 1933, Price:6.995.000, 111.0 m2 , ZipCode:1400 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_5482695483a2cf3375fee9c6b3f655d5.setContent(html_afb1303c4eb0867f0babd62f0436c36f);
        

        marker_d571758a1630e7cf2604263e022d7751.bindPopup(popup_5482695483a2cf3375fee9c6b3f655d5)
        ;

        
    
    
            var marker_da5be861b5dbac31892b27d1d08e9539 = L.marker(
                [55.673475, 12.589755],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_db389d6425918964f0cdcc72fcdd8b43 = L.popup({"maxWidth": "100%"});

        
            var html_00e5f761f6dafc789042d9832258f9f4 = $(`<div id="html_00e5f761f6dafc789042d9832258f9f4" style="width: 100.0%; height: 100.0%;">Year Built: 1933, Price:5.700.000, 98.0 m2 , ZipCode:1400 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_db389d6425918964f0cdcc72fcdd8b43.setContent(html_00e5f761f6dafc789042d9832258f9f4);
        

        marker_da5be861b5dbac31892b27d1d08e9539.bindPopup(popup_db389d6425918964f0cdcc72fcdd8b43)
        ;

        
    
    
            var marker_93b4f530a5b861d0079c5e8cefa2c46a = L.marker(
                [55.671614, 12.592557],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_c2d4c01ae49269db54b687a3e4a395f8 = L.popup({"maxWidth": "100%"});

        
            var html_8c3158a85bf37d45c30aa451b1a8b3dc = $(`<div id="html_8c3158a85bf37d45c30aa451b1a8b3dc" style="width: 100.0%; height: 100.0%;">Year Built: 1903, Price:6.195.000, 95.0 m2 , ZipCode:1400 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_c2d4c01ae49269db54b687a3e4a395f8.setContent(html_8c3158a85bf37d45c30aa451b1a8b3dc);
        

        marker_93b4f530a5b861d0079c5e8cefa2c46a.bindPopup(popup_c2d4c01ae49269db54b687a3e4a395f8)
        ;

        
    
    
            var marker_94dd117c6aaad58f559aaefdb8cb7dd0 = L.marker(
                [55.673652, 12.590241],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_02e4566b156b496801c5e93e0895420c = L.popup({"maxWidth": "100%"});

        
            var html_a03b28dad9cd4dd1b40a855a4868fc39 = $(`<div id="html_a03b28dad9cd4dd1b40a855a4868fc39" style="width: 100.0%; height: 100.0%;">Year Built: 1623, Price:6.995.000, 109.0 m2 , ZipCode:1401 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_02e4566b156b496801c5e93e0895420c.setContent(html_a03b28dad9cd4dd1b40a855a4868fc39);
        

        marker_94dd117c6aaad58f559aaefdb8cb7dd0.bindPopup(popup_02e4566b156b496801c5e93e0895420c)
        ;

        
    
    
            var marker_38fdf24be3d5737f2a7af9c5c4b39310 = L.marker(
                [55.673712, 12.590128],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_75f3e96cc7db5b6bccf92f8cb1a0d850 = L.popup({"maxWidth": "100%"});

        
            var html_8d26161fa7d31ae47038856b3dc58383 = $(`<div id="html_8d26161fa7d31ae47038856b3dc58383" style="width: 100.0%; height: 100.0%;">Year Built: 1623, Price:9.995.000, 134.0 m2 , ZipCode:1401 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_75f3e96cc7db5b6bccf92f8cb1a0d850.setContent(html_8d26161fa7d31ae47038856b3dc58383);
        

        marker_38fdf24be3d5737f2a7af9c5c4b39310.bindPopup(popup_75f3e96cc7db5b6bccf92f8cb1a0d850)
        ;

        
    
    
            var marker_9af6edb552c1ec3c690811cf4a726595 = L.marker(
                [55.673872, 12.589885],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_12f866a87037f4a36b49690fc3f6ffa6 = L.popup({"maxWidth": "100%"});

        
            var html_dd9abb4d6f80681ecb484f6465973aaa = $(`<div id="html_dd9abb4d6f80681ecb484f6465973aaa" style="width: 100.0%; height: 100.0%;">Year Built: 1623, Price:21.500.000, 216.0 m2 , ZipCode:1401 ,  Rooms:5, HomeType:Ejerlejlighed</div>`)[0];
            popup_12f866a87037f4a36b49690fc3f6ffa6.setContent(html_dd9abb4d6f80681ecb484f6465973aaa);
        

        marker_9af6edb552c1ec3c690811cf4a726595.bindPopup(popup_12f866a87037f4a36b49690fc3f6ffa6)
        ;

        
    
    
            var marker_3826f0d2d5544d1c7d88b87d1fac4a22 = L.marker(
                [55.673378, 12.589016],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_aa8c3fa4737fbc22d41ebde7e77b1868 = L.popup({"maxWidth": "100%"});

        
            var html_e5a14090efa66a8b23206319516d2bd6 = $(`<div id="html_e5a14090efa66a8b23206319516d2bd6" style="width: 100.0%; height: 100.0%;">Year Built: 1653, Price:7.195.000, 104.0 m2 , ZipCode:1401 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_aa8c3fa4737fbc22d41ebde7e77b1868.setContent(html_e5a14090efa66a8b23206319516d2bd6);
        

        marker_3826f0d2d5544d1c7d88b87d1fac4a22.bindPopup(popup_aa8c3fa4737fbc22d41ebde7e77b1868)
        ;

        
    
    
            var marker_89b4c548bd344f54c10cc0a0609dc73b = L.marker(
                [55.674841, 12.591394],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_87da18cd31d2d28b6ede52d13eb0bba6 = L.popup({"maxWidth": "100%"});

        
            var html_2e6d39adf9b7699a905298f8904e33f5 = $(`<div id="html_2e6d39adf9b7699a905298f8904e33f5" style="width: 100.0%; height: 100.0%;">Year Built: 1700, Price:5.995.000, 77.0 m2 , ZipCode:1401 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_87da18cd31d2d28b6ede52d13eb0bba6.setContent(html_2e6d39adf9b7699a905298f8904e33f5);
        

        marker_89b4c548bd344f54c10cc0a0609dc73b.bindPopup(popup_87da18cd31d2d28b6ede52d13eb0bba6)
        ;

        
    
    
            var marker_191907d2a56a483b1ab85c4d5925daf1 = L.marker(
                [55.673092, 12.589051],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_5d78d82c004dcf98747420eeecb12518 = L.popup({"maxWidth": "100%"});

        
            var html_40730cc87e3cb2b68192de1b2fa795e1 = $(`<div id="html_40730cc87e3cb2b68192de1b2fa795e1" style="width: 100.0%; height: 100.0%;">Year Built: 1800, Price:8.995.000, 130.0 m2 , ZipCode:1401 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_5d78d82c004dcf98747420eeecb12518.setContent(html_40730cc87e3cb2b68192de1b2fa795e1);
        

        marker_191907d2a56a483b1ab85c4d5925daf1.bindPopup(popup_5d78d82c004dcf98747420eeecb12518)
        ;

        
    
    
            var marker_005ac8ac55dac3ee92b0fc283b14d5e8 = L.marker(
                [55.676881, 12.59593],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_449b4ea63297946ef983c62566051fad = L.popup({"maxWidth": "100%"});

        
            var html_563ff08326ffffc93c371b7ca5a5d2e8 = $(`<div id="html_563ff08326ffffc93c371b7ca5a5d2e8" style="width: 100.0%; height: 100.0%;">Year Built: 2014, Price:14.998.000, 141.0 m2 , ZipCode:1401 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_449b4ea63297946ef983c62566051fad.setContent(html_563ff08326ffffc93c371b7ca5a5d2e8);
        

        marker_005ac8ac55dac3ee92b0fc283b14d5e8.bindPopup(popup_449b4ea63297946ef983c62566051fad)
        ;

        
    
    
            var marker_5f5f6129e15112c84b94b445383f9490 = L.marker(
                [55.673836, 12.590964],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_bb8dbd39093d8c33f540645f35953542 = L.popup({"maxWidth": "100%"});

        
            var html_b85c58f9bf7e0f7fd9578bba3b916760 = $(`<div id="html_b85c58f9bf7e0f7fd9578bba3b916760" style="width: 100.0%; height: 100.0%;">Year Built: 1800, Price:6.495.000, 101.0 m2 , ZipCode:1408 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_bb8dbd39093d8c33f540645f35953542.setContent(html_b85c58f9bf7e0f7fd9578bba3b916760);
        

        marker_5f5f6129e15112c84b94b445383f9490.bindPopup(popup_bb8dbd39093d8c33f540645f35953542)
        ;

        
    
    
            var marker_24db30470ea4cf1f8ddf2f85af55070f = L.marker(
                [55.671332, 12.587434],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_2628a5184572c86e22f705c1153acb13 = L.popup({"maxWidth": "100%"});

        
            var html_8c54eca612464cce2361bbf076ebefc1 = $(`<div id="html_8c54eca612464cce2361bbf076ebefc1" style="width: 100.0%; height: 100.0%;">Year Built: 2001, Price:7.495.000, 123.0 m2 , ZipCode:1408 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_2628a5184572c86e22f705c1153acb13.setContent(html_8c54eca612464cce2361bbf076ebefc1);
        

        marker_24db30470ea4cf1f8ddf2f85af55070f.bindPopup(popup_2628a5184572c86e22f705c1153acb13)
        ;

        
    
    
            var marker_62e719caf61681f040a889ffb64ae650 = L.marker(
                [55.673329, 12.59048],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_be0ed30bca2d8d13a313cc57ebee09e7 = L.popup({"maxWidth": "100%"});

        
            var html_57f19d48eb524499f0501b3594fdf93f = $(`<div id="html_57f19d48eb524499f0501b3594fdf93f" style="width: 100.0%; height: 100.0%;">Year Built: 1778, Price:7.600.000, 93.0 m2 , ZipCode:1408 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_be0ed30bca2d8d13a313cc57ebee09e7.setContent(html_57f19d48eb524499f0501b3594fdf93f);
        

        marker_62e719caf61681f040a889ffb64ae650.bindPopup(popup_be0ed30bca2d8d13a313cc57ebee09e7)
        ;

        
    
    
            var marker_ace5a0187a4ce4f349da724949c65ebc = L.marker(
                [55.67278, 12.5896],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_01f5af8ff0e556e4ae7ad98adeaea041 = L.popup({"maxWidth": "100%"});

        
            var html_ee5aa36891f220fcbef0315744c6e689 = $(`<div id="html_ee5aa36891f220fcbef0315744c6e689" style="width: 100.0%; height: 100.0%;">Year Built: 1858, Price:4.395.000, 88.0 m2 , ZipCode:1408 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_01f5af8ff0e556e4ae7ad98adeaea041.setContent(html_ee5aa36891f220fcbef0315744c6e689);
        

        marker_ace5a0187a4ce4f349da724949c65ebc.bindPopup(popup_01f5af8ff0e556e4ae7ad98adeaea041)
        ;

        
    
    
            var marker_974609dcb31fd7f345fc9aa05a0d4dd1 = L.marker(
                [55.671435, 12.587005],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_3e0b50a010500b68fa4542d4eb88e18c = L.popup({"maxWidth": "100%"});

        
            var html_82f4d55875d41d53b3991648efa9dccd = $(`<div id="html_82f4d55875d41d53b3991648efa9dccd" style="width: 100.0%; height: 100.0%;">Year Built: 2002, Price:7.985.000, 108.0 m2 , ZipCode:1408 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_3e0b50a010500b68fa4542d4eb88e18c.setContent(html_82f4d55875d41d53b3991648efa9dccd);
        

        marker_974609dcb31fd7f345fc9aa05a0d4dd1.bindPopup(popup_3e0b50a010500b68fa4542d4eb88e18c)
        ;

        
    
    
            var marker_53404c9642b118235d2461225168c04b = L.marker(
                [55.670139, 12.586306],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_1e4b62525278a0a4671c8cf5fabd5c89 = L.popup({"maxWidth": "100%"});

        
            var html_70eddc8d5fccc74daf44c07efeea6239 = $(`<div id="html_70eddc8d5fccc74daf44c07efeea6239" style="width: 100.0%; height: 100.0%;">Year Built: 1727, Price:5.495.000, 82.0 m2 , ZipCode:1411 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_1e4b62525278a0a4671c8cf5fabd5c89.setContent(html_70eddc8d5fccc74daf44c07efeea6239);
        

        marker_53404c9642b118235d2461225168c04b.bindPopup(popup_1e4b62525278a0a4671c8cf5fabd5c89)
        ;

        
    
    
            var marker_9ae8d895b4302def630bd35e893abb0b = L.marker(
                [55.674014, 12.591104],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_f1417ce7169833cee50da8a2286e248a = L.popup({"maxWidth": "100%"});

        
            var html_f3c93358e333fd4b0801ef15fc489b4c = $(`<div id="html_f3c93358e333fd4b0801ef15fc489b4c" style="width: 100.0%; height: 100.0%;">Year Built: 1848, Price:3.695.000, 54.0 m2 , ZipCode:1416 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_f1417ce7169833cee50da8a2286e248a.setContent(html_f3c93358e333fd4b0801ef15fc489b4c);
        

        marker_9ae8d895b4302def630bd35e893abb0b.bindPopup(popup_f1417ce7169833cee50da8a2286e248a)
        ;

        
    
    
            var marker_c3cbead47b9067235b6c1b0caca91b5e = L.marker(
                [55.673206, 12.59318],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_10db4739a93b7d0bcbebc9959f3094c8 = L.popup({"maxWidth": "100%"});

        
            var html_77c216e3828cafbce2b8839f8e3dfad6 = $(`<div id="html_77c216e3828cafbce2b8839f8e3dfad6" style="width: 100.0%; height: 100.0%;">Year Built: 1938, Price:4.298.000, 81.0 m2 , ZipCode:1416 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_10db4739a93b7d0bcbebc9959f3094c8.setContent(html_77c216e3828cafbce2b8839f8e3dfad6);
        

        marker_c3cbead47b9067235b6c1b0caca91b5e.bindPopup(popup_10db4739a93b7d0bcbebc9959f3094c8)
        ;

        
    
    
            var marker_53c91f993f5b354f5a6e105c8c27fc82 = L.marker(
                [55.673292, 12.593018],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_2a039e2173cb7eb580ef2a1f71101375 = L.popup({"maxWidth": "100%"});

        
            var html_91a6efcd841d655c350e41b8ef3c548a = $(`<div id="html_91a6efcd841d655c350e41b8ef3c548a" style="width: 100.0%; height: 100.0%;">Year Built: 1938, Price:2.995.000, 42.0 m2 , ZipCode:1416 ,  Rooms:1, HomeType:Ejerlejlighed</div>`)[0];
            popup_2a039e2173cb7eb580ef2a1f71101375.setContent(html_91a6efcd841d655c350e41b8ef3c548a);
        

        marker_53c91f993f5b354f5a6e105c8c27fc82.bindPopup(popup_2a039e2173cb7eb580ef2a1f71101375)
        ;

        
    
    
            var marker_91b89173f5acb3736ff77090a4a2f8b2 = L.marker(
                [55.670963, 12.590477],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_1954607d2e350e66961b8e3dac7610df = L.popup({"maxWidth": "100%"});

        
            var html_98395ea7631f50946abdc8154e5ad018 = $(`<div id="html_98395ea7631f50946abdc8154e5ad018" style="width: 100.0%; height: 100.0%;">Year Built: 1972, Price:3.995.000, 65.0 m2 , ZipCode:1420 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_1954607d2e350e66961b8e3dac7610df.setContent(html_98395ea7631f50946abdc8154e5ad018);
        

        marker_91b89173f5acb3736ff77090a4a2f8b2.bindPopup(popup_1954607d2e350e66961b8e3dac7610df)
        ;

        
    
    
            var marker_24ed4ebae84ed1f1413d1a0fe89c3c49 = L.marker(
                [55.67024, 12.590458],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_f87e71a7b1cda2fa120d3c1fb8641dc7 = L.popup({"maxWidth": "100%"});

        
            var html_e09bc238107b482a73af26ef78e38973 = $(`<div id="html_e09bc238107b482a73af26ef78e38973" style="width: 100.0%; height: 100.0%;">Year Built: 1914, Price:3.695.000, 54.0 m2 , ZipCode:1422 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_f87e71a7b1cda2fa120d3c1fb8641dc7.setContent(html_e09bc238107b482a73af26ef78e38973);
        

        marker_24ed4ebae84ed1f1413d1a0fe89c3c49.bindPopup(popup_f87e71a7b1cda2fa120d3c1fb8641dc7)
        ;

        
    
    
            var marker_107aaee45067790e19ab767abde57277 = L.marker(
                [55.671532, 12.592549],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_8f23d8f77bbd836b83f1c35550e4e801 = L.popup({"maxWidth": "100%"});

        
            var html_d83d265a8af40d375d5b0eef97afdde8 = $(`<div id="html_d83d265a8af40d375d5b0eef97afdde8" style="width: 100.0%; height: 100.0%;">Year Built: 1903, Price:3.998.000, 61.0 m2 , ZipCode:1422 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_8f23d8f77bbd836b83f1c35550e4e801.setContent(html_d83d265a8af40d375d5b0eef97afdde8);
        

        marker_107aaee45067790e19ab767abde57277.bindPopup(popup_8f23d8f77bbd836b83f1c35550e4e801)
        ;

        
    
    
            var marker_b3c25886caf348d5770207905c609c05 = L.marker(
                [55.671416, 12.592365],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_d29bc17c88496bc0a26ab23ff9777fab = L.popup({"maxWidth": "100%"});

        
            var html_5dead9c433683d8860d086725fea4e74 = $(`<div id="html_5dead9c433683d8860d086725fea4e74" style="width: 100.0%; height: 100.0%;">Year Built: 1903, Price:2.999.000, 47.0 m2 , ZipCode:1422 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_d29bc17c88496bc0a26ab23ff9777fab.setContent(html_5dead9c433683d8860d086725fea4e74);
        

        marker_b3c25886caf348d5770207905c609c05.bindPopup(popup_d29bc17c88496bc0a26ab23ff9777fab)
        ;

        
    
    
            var marker_21968849f7a6ce6f1faf54324971fba7 = L.marker(
                [55.670922, 12.592961],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_e614cc7fc3610b1e4d0b02edbd4f7382 = L.popup({"maxWidth": "100%"});

        
            var html_a4559d5a8f19e2013c36728adb1389b2 = $(`<div id="html_a4559d5a8f19e2013c36728adb1389b2" style="width: 100.0%; height: 100.0%;">Year Built: 1870, Price:6.195.000, 82.0 m2 , ZipCode:1423 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_e614cc7fc3610b1e4d0b02edbd4f7382.setContent(html_a4559d5a8f19e2013c36728adb1389b2);
        

        marker_21968849f7a6ce6f1faf54324971fba7.bindPopup(popup_e614cc7fc3610b1e4d0b02edbd4f7382)
        ;

        
    
    
            var marker_85deaaa2ecc975e818cc6f69f0ed3ace = L.marker(
                [55.670006, 12.589926],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_3268e983f583587b5b792df4b6038f1e = L.popup({"maxWidth": "100%"});

        
            var html_51da706afd40ecb3993e6b40d7a0a630 = $(`<div id="html_51da706afd40ecb3993e6b40d7a0a630" style="width: 100.0%; height: 100.0%;">Year Built: 1914, Price:4.195.000, 60.0 m2 , ZipCode:1424 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_3268e983f583587b5b792df4b6038f1e.setContent(html_51da706afd40ecb3993e6b40d7a0a630);
        

        marker_85deaaa2ecc975e818cc6f69f0ed3ace.bindPopup(popup_3268e983f583587b5b792df4b6038f1e)
        ;

        
    
    
            var marker_028ff0980fa1ae58b38b67017962b8f1 = L.marker(
                [55.670068, 12.587664],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_e2fcefc18313e465ca719a8c8cd3a3e3 = L.popup({"maxWidth": "100%"});

        
            var html_4e4c9fd050197ca71a3365903f4d7f7f = $(`<div id="html_4e4c9fd050197ca71a3365903f4d7f7f" style="width: 100.0%; height: 100.0%;">Year Built: 1894, Price:4.995.000, 76.0 m2 , ZipCode:1424 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_e2fcefc18313e465ca719a8c8cd3a3e3.setContent(html_4e4c9fd050197ca71a3365903f4d7f7f);
        

        marker_028ff0980fa1ae58b38b67017962b8f1.bindPopup(popup_e2fcefc18313e465ca719a8c8cd3a3e3)
        ;

        
    
    
            var marker_f52624044476574112aa453f85a1037e = L.marker(
                [55.670068, 12.587664],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_932f5c3d7be06f8d0577d19516109799 = L.popup({"maxWidth": "100%"});

        
            var html_96f28de234a08512dcd38ee26ce03d24 = $(`<div id="html_96f28de234a08512dcd38ee26ce03d24" style="width: 100.0%; height: 100.0%;">Year Built: 1894, Price:3.995.000, 57.0 m2 , ZipCode:1424 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_932f5c3d7be06f8d0577d19516109799.setContent(html_96f28de234a08512dcd38ee26ce03d24);
        

        marker_f52624044476574112aa453f85a1037e.bindPopup(popup_932f5c3d7be06f8d0577d19516109799)
        ;

        
    
    
            var marker_d56dc28b16a4c3b854dc352de02ed016 = L.marker(
                [55.672052, 12.594456],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_a9589b0301dbeb862f8c6f5f9174b32a = L.popup({"maxWidth": "100%"});

        
            var html_613bda8c608d9fccc1948b28c527551e = $(`<div id="html_613bda8c608d9fccc1948b28c527551e" style="width: 100.0%; height: 100.0%;">Year Built: 1938, Price:3.450.000, 55.0 m2 , ZipCode:1425 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_a9589b0301dbeb862f8c6f5f9174b32a.setContent(html_613bda8c608d9fccc1948b28c527551e);
        

        marker_d56dc28b16a4c3b854dc352de02ed016.bindPopup(popup_a9589b0301dbeb862f8c6f5f9174b32a)
        ;

        
    
    
            var marker_53a1ede34417a6646cd198d14b1d4ac0 = L.marker(
                [55.671683, 12.59349],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_e2baec0b2c44cb3d111f0ce5c41f1cd8 = L.popup({"maxWidth": "100%"});

        
            var html_6fdb445edc1e62631903c36c8d0db8f9 = $(`<div id="html_6fdb445edc1e62631903c36c8d0db8f9" style="width: 100.0%; height: 100.0%;">Year Built: 1938, Price:4.795.000, 98.0 m2 , ZipCode:1425 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_e2baec0b2c44cb3d111f0ce5c41f1cd8.setContent(html_6fdb445edc1e62631903c36c8d0db8f9);
        

        marker_53a1ede34417a6646cd198d14b1d4ac0.bindPopup(popup_e2baec0b2c44cb3d111f0ce5c41f1cd8)
        ;

        
    
    
            var marker_8b5a02ba675052d4e784944d85f66330 = L.marker(
                [55.671942, 12.593924],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_663fec4822a7b2d3c6bc248c124c5918 = L.popup({"maxWidth": "100%"});

        
            var html_cd27de085638afaff51b827479649f5b = $(`<div id="html_cd27de085638afaff51b827479649f5b" style="width: 100.0%; height: 100.0%;">Year Built: 1938, Price:4.695.000, 91.0 m2 , ZipCode:1425 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_663fec4822a7b2d3c6bc248c124c5918.setContent(html_cd27de085638afaff51b827479649f5b);
        

        marker_8b5a02ba675052d4e784944d85f66330.bindPopup(popup_663fec4822a7b2d3c6bc248c124c5918)
        ;

        
    
    
            var marker_7da37dc4e00cd74f479696083f448802 = L.marker(
                [55.675162, 12.596705],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_1515324d609377ba5dbaba95ec95c801 = L.popup({"maxWidth": "100%"});

        
            var html_6298fcb0ce18073e2cd3c82c09e24852 = $(`<div id="html_6298fcb0ce18073e2cd3c82c09e24852" style="width: 100.0%; height: 100.0%;">Year Built: 1902, Price:4.998.000, 82.0 m2 , ZipCode:1427 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_1515324d609377ba5dbaba95ec95c801.setContent(html_6298fcb0ce18073e2cd3c82c09e24852);
        

        marker_7da37dc4e00cd74f479696083f448802.bindPopup(popup_1515324d609377ba5dbaba95ec95c801)
        ;

        
    
    
            var marker_dedd968222fc20a70f67f6d11e2743bf = L.marker(
                [55.674962, 12.597289],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_44e7a70db5035393bf0d184b868ec652 = L.popup({"maxWidth": "100%"});

        
            var html_01dbac4f345c770edfe3494ed3992da2 = $(`<div id="html_01dbac4f345c770edfe3494ed3992da2" style="width: 100.0%; height: 100.0%;">Year Built: 1902, Price:6.195.000, 81.0 m2 , ZipCode:1427 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_44e7a70db5035393bf0d184b868ec652.setContent(html_01dbac4f345c770edfe3494ed3992da2);
        

        marker_dedd968222fc20a70f67f6d11e2743bf.bindPopup(popup_44e7a70db5035393bf0d184b868ec652)
        ;

        
    
    
            var marker_779d0a3cbafb96bacf22b4a39c0e7bf8 = L.marker(
                [55.675198, 12.597279],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_929872c1c6c5611abd5f973b77c0d9f1 = L.popup({"maxWidth": "100%"});

        
            var html_de7699ab53224b079f5471c16d34fb86 = $(`<div id="html_de7699ab53224b079f5471c16d34fb86" style="width: 100.0%; height: 100.0%;">Year Built: 1901, Price:4.795.000, 71.0 m2 , ZipCode:1427 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_929872c1c6c5611abd5f973b77c0d9f1.setContent(html_de7699ab53224b079f5471c16d34fb86);
        

        marker_779d0a3cbafb96bacf22b4a39c0e7bf8.bindPopup(popup_929872c1c6c5611abd5f973b77c0d9f1)
        ;

        
    
    
            var marker_ea9381cedb25d7c09627553bc8db30ee = L.marker(
                [55.674849, 12.597623],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_a4832c04d3bad96bd0d3dc8c85be683d = L.popup({"maxWidth": "100%"});

        
            var html_09a936ae50d4b47cea023f63c65f5490 = $(`<div id="html_09a936ae50d4b47cea023f63c65f5490" style="width: 100.0%; height: 100.0%;">Year Built: 1902, Price:4.995.000, 65.0 m2 , ZipCode:1427 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_a4832c04d3bad96bd0d3dc8c85be683d.setContent(html_09a936ae50d4b47cea023f63c65f5490);
        

        marker_ea9381cedb25d7c09627553bc8db30ee.bindPopup(popup_a4832c04d3bad96bd0d3dc8c85be683d)
        ;

        
    
    
            var marker_9925a942d7ddce0a433ffe958c4a174c = L.marker(
                [55.675672, 12.598571],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_fbb34700b997ff7f632f0ad26c7e2ff5 = L.popup({"maxWidth": "100%"});

        
            var html_70ae07a007c09318f889fb620d303118 = $(`<div id="html_70ae07a007c09318f889fb620d303118" style="width: 100.0%; height: 100.0%;">Year Built: 1901, Price:4.195.000, 52.0 m2 , ZipCode:1429 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_fbb34700b997ff7f632f0ad26c7e2ff5.setContent(html_70ae07a007c09318f889fb620d303118);
        

        marker_9925a942d7ddce0a433ffe958c4a174c.bindPopup(popup_fbb34700b997ff7f632f0ad26c7e2ff5)
        ;

        
    
    
            var marker_0acf77efeba8d560b079450bf464ec86 = L.marker(
                [55.675829, 12.598764],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_af3e5f62b576a769390688143a9bfe8d = L.popup({"maxWidth": "100%"});

        
            var html_692c29faa941aa4241bfe01e7be6e658 = $(`<div id="html_692c29faa941aa4241bfe01e7be6e658" style="width: 100.0%; height: 100.0%;">Year Built: 1901, Price:3.700.000, 51.0 m2 , ZipCode:1429 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_af3e5f62b576a769390688143a9bfe8d.setContent(html_692c29faa941aa4241bfe01e7be6e658);
        

        marker_0acf77efeba8d560b079450bf464ec86.bindPopup(popup_af3e5f62b576a769390688143a9bfe8d)
        ;

        
    
    
            var marker_77d11676ab41d1bf837466aac23b4dd2 = L.marker(
                [55.675899, 12.598851],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_67080d84e4e5032777a9e3a86cb6c10e = L.popup({"maxWidth": "100%"});

        
            var html_cf8262cfe3d585304795b2271306d2cf = $(`<div id="html_cf8262cfe3d585304795b2271306d2cf" style="width: 100.0%; height: 100.0%;">Year Built: 1901, Price:3.550.000, 52.0 m2 , ZipCode:1429 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_67080d84e4e5032777a9e3a86cb6c10e.setContent(html_cf8262cfe3d585304795b2271306d2cf);
        

        marker_77d11676ab41d1bf837466aac23b4dd2.bindPopup(popup_67080d84e4e5032777a9e3a86cb6c10e)
        ;

        
    
    
            var marker_6e6cb921b0acd5d7d67973c050a283bc = L.marker(
                [55.675899, 12.598851],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_2d06e8b3b99c4c1956bd71932a44579d = L.popup({"maxWidth": "100%"});

        
            var html_7d24cbbc8c4758e5131198810c5b8030 = $(`<div id="html_7d24cbbc8c4758e5131198810c5b8030" style="width: 100.0%; height: 100.0%;">Year Built: 1901, Price:2.999.000, 45.0 m2 , ZipCode:1429 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_2d06e8b3b99c4c1956bd71932a44579d.setContent(html_7d24cbbc8c4758e5131198810c5b8030);
        

        marker_6e6cb921b0acd5d7d67973c050a283bc.bindPopup(popup_2d06e8b3b99c4c1956bd71932a44579d)
        ;

        
    
    
            var marker_e413805453e3bfdf74332a60b9130b6b = L.marker(
                [55.6764988, 12.5988617],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_b1727c3af1298bc201c355c9c8c61b8b = L.popup({"maxWidth": "100%"});

        
            var html_a59eea954429dac984d37b81fcef96d2 = $(`<div id="html_a59eea954429dac984d37b81fcef96d2" style="width: 100.0%; height: 100.0%;">Year Built: 1901, Price:5.000.000, 74.0 m2 , ZipCode:1430 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_b1727c3af1298bc201c355c9c8c61b8b.setContent(html_a59eea954429dac984d37b81fcef96d2);
        

        marker_e413805453e3bfdf74332a60b9130b6b.bindPopup(popup_b1727c3af1298bc201c355c9c8c61b8b)
        ;

        
    
    
            var marker_44716f56ce59a9e3bbf8d71084411277 = L.marker(
                [55.686472, 12.615548],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_bbcf17890c74ac97f9a8a661c74e7053 = L.popup({"maxWidth": "100%"});

        
            var html_bc7f5a05f8f0846c99deb3d400935b3b = $(`<div id="html_bc7f5a05f8f0846c99deb3d400935b3b" style="width: 100.0%; height: 100.0%;">Year Built: 2014, Price:5.495.000, 92.0 m2 , ZipCode:1432 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_bbcf17890c74ac97f9a8a661c74e7053.setContent(html_bc7f5a05f8f0846c99deb3d400935b3b);
        

        marker_44716f56ce59a9e3bbf8d71084411277.bindPopup(popup_bbcf17890c74ac97f9a8a661c74e7053)
        ;

        
    
    
            var marker_2743448b420e8fcf0d0e7be20c73af60 = L.marker(
                [55.685961, 12.615573],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_7ef278a3c747b2f6276220b590a16b3b = L.popup({"maxWidth": "100%"});

        
            var html_1917897159f5560528dcfffd55bb33ec = $(`<div id="html_1917897159f5560528dcfffd55bb33ec" style="width: 100.0%; height: 100.0%;">Year Built: 2014, Price:5.295.000, 93.0 m2 , ZipCode:1432 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_7ef278a3c747b2f6276220b590a16b3b.setContent(html_1917897159f5560528dcfffd55bb33ec);
        

        marker_2743448b420e8fcf0d0e7be20c73af60.bindPopup(popup_7ef278a3c747b2f6276220b590a16b3b)
        ;

        
    
    
            var marker_6e31bfe9a56c5f57879cb513b0470ae6 = L.marker(
                [55.686472, 12.615548],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_31596de0c2405850a4ab26f3a4342cb9 = L.popup({"maxWidth": "100%"});

        
            var html_edbcb16fd51c9fb39d5778cd6b448c31 = $(`<div id="html_edbcb16fd51c9fb39d5778cd6b448c31" style="width: 100.0%; height: 100.0%;">Year Built: 2014, Price:10.995.000, 141.0 m2 , ZipCode:1432 ,  Rooms:5, HomeType:Ejerlejlighed</div>`)[0];
            popup_31596de0c2405850a4ab26f3a4342cb9.setContent(html_edbcb16fd51c9fb39d5778cd6b448c31);
        

        marker_6e31bfe9a56c5f57879cb513b0470ae6.bindPopup(popup_31596de0c2405850a4ab26f3a4342cb9)
        ;

        
    
    
            var marker_9f534d98bc9ab6a201a3594cbaafe2fe = L.marker(
                [55.679353, 12.604254],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_5fa587a84b3859ce6208e445cf6b087b = L.popup({"maxWidth": "100%"});

        
            var html_54488d321aacf9901c8802cb2590598d = $(`<div id="html_54488d321aacf9901c8802cb2590598d" style="width: 100.0%; height: 100.0%;">Year Built: 2005, Price:6.350.000, 100.0 m2 , ZipCode:1437 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_5fa587a84b3859ce6208e445cf6b087b.setContent(html_54488d321aacf9901c8802cb2590598d);
        

        marker_9f534d98bc9ab6a201a3594cbaafe2fe.bindPopup(popup_5fa587a84b3859ce6208e445cf6b087b)
        ;

        
    
    
            var marker_311a701d04421f662a681f8120dcb23f = L.marker(
                [55.679978, 12.568262],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_2c8fd519355fb8328571f72b80f26529 = L.popup({"maxWidth": "100%"});

        
            var html_ef8e37068aa5a5fc732fa540b50ad401 = $(`<div id="html_ef8e37068aa5a5fc732fa540b50ad401" style="width: 100.0%; height: 100.0%;">Year Built: 1875, Price:5.295.000, 72.0 m2 , ZipCode:1452 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_2c8fd519355fb8328571f72b80f26529.setContent(html_ef8e37068aa5a5fc732fa540b50ad401);
        

        marker_311a701d04421f662a681f8120dcb23f.bindPopup(popup_2c8fd519355fb8328571f72b80f26529)
        ;

        
    
    
            var marker_7ad1068b0cda03f1389e287964755f73 = L.marker(
                [55.679432, 12.568257],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_b1ea09d8e29272f2fb9f710d76730836 = L.popup({"maxWidth": "100%"});

        
            var html_57ea81e468890c4075bc6a230624bef1 = $(`<div id="html_57ea81e468890c4075bc6a230624bef1" style="width: 100.0%; height: 100.0%;">Year Built: 1801, Price:3.245.000, 51.0 m2 , ZipCode:1452 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_b1ea09d8e29272f2fb9f710d76730836.setContent(html_57ea81e468890c4075bc6a230624bef1);
        

        marker_7ad1068b0cda03f1389e287964755f73.bindPopup(popup_b1ea09d8e29272f2fb9f710d76730836)
        ;

        
    
    
            var marker_f876caaf6d7f6a9524332d85fcb8aef4 = L.marker(
                [55.678748, 12.569646],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_9ce906ee17a6c0b602b6fee1cac0f597 = L.popup({"maxWidth": "100%"});

        
            var html_99504f2ba330791f7ba9f11763373179 = $(`<div id="html_99504f2ba330791f7ba9f11763373179" style="width: 100.0%; height: 100.0%;">Year Built: 1798, Price:5.495.000, 92.0 m2 , ZipCode:1455 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_9ce906ee17a6c0b602b6fee1cac0f597.setContent(html_99504f2ba330791f7ba9f11763373179);
        

        marker_f876caaf6d7f6a9524332d85fcb8aef4.bindPopup(popup_9ce906ee17a6c0b602b6fee1cac0f597)
        ;

        
    
    
            var marker_d3065864d19a1ae35e96efc343d940e2 = L.marker(
                [55.676709, 12.571609],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_e5acbf1b362898bf114dfb17e506a4a6 = L.popup({"maxWidth": "100%"});

        
            var html_d6d82d75608abac6df415c67273ec4d4 = $(`<div id="html_d6d82d75608abac6df415c67273ec4d4" style="width: 100.0%; height: 100.0%;">Year Built: 1784, Price:7.250.000, 120.0 m2 , ZipCode:1458 ,  Rooms:5, HomeType:Ejerlejlighed</div>`)[0];
            popup_e5acbf1b362898bf114dfb17e506a4a6.setContent(html_d6d82d75608abac6df415c67273ec4d4);
        

        marker_d3065864d19a1ae35e96efc343d940e2.bindPopup(popup_e5acbf1b362898bf114dfb17e506a4a6)
        ;

        
    
    
            var marker_f1412b91f86eac000a76a74542789fd2 = L.marker(
                [55.676092, 12.571469],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_4e086e295056777f16fc7bfadc3b765e = L.popup({"maxWidth": "100%"});

        
            var html_33459d79075a94e8a1863af68c3135c8 = $(`<div id="html_33459d79075a94e8a1863af68c3135c8" style="width: 100.0%; height: 100.0%;">Year Built: 1799, Price:5.500.000, 116.0 m2 , ZipCode:1462 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_4e086e295056777f16fc7bfadc3b765e.setContent(html_33459d79075a94e8a1863af68c3135c8);
        

        marker_f1412b91f86eac000a76a74542789fd2.bindPopup(popup_4e086e295056777f16fc7bfadc3b765e)
        ;

        
    
    
            var marker_2464eb429386698d18b8eb398bcb80af = L.marker(
                [55.676468, 12.571678],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_99d2555fd722e29aeecf7c04d668a4f6 = L.popup({"maxWidth": "100%"});

        
            var html_6e7186cfb753d42e9bbc5709376d0bdc = $(`<div id="html_6e7186cfb753d42e9bbc5709376d0bdc" style="width: 100.0%; height: 100.0%;">Year Built: 1797, Price:6.649.000, 99.0 m2 , ZipCode:1462 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_99d2555fd722e29aeecf7c04d668a4f6.setContent(html_6e7186cfb753d42e9bbc5709376d0bdc);
        

        marker_2464eb429386698d18b8eb398bcb80af.bindPopup(popup_99d2555fd722e29aeecf7c04d668a4f6)
        ;

        
    
    
            var marker_52fdda35c9f11c3855082f59f77811c1 = L.marker(
                [55.676824, 12.574405],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_2edc87bb3f7bb018639698857eec7bc5 = L.popup({"maxWidth": "100%"});

        
            var html_32ea8fba9930c37c17cffece3000aad9 = $(`<div id="html_32ea8fba9930c37c17cffece3000aad9" style="width: 100.0%; height: 100.0%;">Year Built: 1798, Price:6.795.000, 119.0 m2 , ZipCode:1466 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_2edc87bb3f7bb018639698857eec7bc5.setContent(html_32ea8fba9930c37c17cffece3000aad9);
        

        marker_52fdda35c9f11c3855082f59f77811c1.bindPopup(popup_2edc87bb3f7bb018639698857eec7bc5)
        ;

        
    
    
            var marker_3ac38a88f0404d7502e13a926981486b = L.marker(
                [55.676911, 12.573876],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_848c761941fbe13a280d3654d850efa8 = L.popup({"maxWidth": "100%"});

        
            var html_966ca650a5eed379e37b8e149f95bc1c = $(`<div id="html_966ca650a5eed379e37b8e149f95bc1c" style="width: 100.0%; height: 100.0%;">Year Built: 1796, Price:7.499.000, 122.0 m2 , ZipCode:1466 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_848c761941fbe13a280d3654d850efa8.setContent(html_966ca650a5eed379e37b8e149f95bc1c);
        

        marker_3ac38a88f0404d7502e13a926981486b.bindPopup(popup_848c761941fbe13a280d3654d850efa8)
        ;

        
    
    
            var marker_ca5fb9bf54d88b3115c429fd495358c2 = L.marker(
                [55.675676, 12.573748],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_d39151d17d67312f1427b0a5b198997d = L.popup({"maxWidth": "100%"});

        
            var html_5c9f83ca3e2bc911998d8fb9f3178705 = $(`<div id="html_5c9f83ca3e2bc911998d8fb9f3178705" style="width: 100.0%; height: 100.0%;">Year Built: 1877, Price:8.675.000, 147.0 m2 , ZipCode:1468 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_d39151d17d67312f1427b0a5b198997d.setContent(html_5c9f83ca3e2bc911998d8fb9f3178705);
        

        marker_ca5fb9bf54d88b3115c429fd495358c2.bindPopup(popup_d39151d17d67312f1427b0a5b198997d)
        ;

        
    
    
            var marker_81b5d9a51388a30030f2482de8c9ac44 = L.marker(
                [55.675678, 12.573846],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_18092b70c3803f0fea1c234447691f70 = L.popup({"maxWidth": "100%"});

        
            var html_21f4699b1c5a8cc6a5b23dfdf21f8b83 = $(`<div id="html_21f4699b1c5a8cc6a5b23dfdf21f8b83" style="width: 100.0%; height: 100.0%;">Year Built: 1877, Price:7.250.000, 121.0 m2 , ZipCode:1468 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_18092b70c3803f0fea1c234447691f70.setContent(html_21f4699b1c5a8cc6a5b23dfdf21f8b83);
        

        marker_81b5d9a51388a30030f2482de8c9ac44.bindPopup(popup_18092b70c3803f0fea1c234447691f70)
        ;

        
    
    
            var marker_0a841839c26973631de7b8bf97cd9425 = L.marker(
                [55.675477, 12.574221],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_e5fde96915529623e60e2415e6d892b4 = L.popup({"maxWidth": "100%"});

        
            var html_2dbf10103fd67f0ba20ec6f1c67ff444 = $(`<div id="html_2dbf10103fd67f0ba20ec6f1c67ff444" style="width: 100.0%; height: 100.0%;">Year Built: 1867, Price:7.350.000, 92.0 m2 , ZipCode:1468 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_e5fde96915529623e60e2415e6d892b4.setContent(html_2dbf10103fd67f0ba20ec6f1c67ff444);
        

        marker_0a841839c26973631de7b8bf97cd9425.bindPopup(popup_e5fde96915529623e60e2415e6d892b4)
        ;

        
    
    
            var marker_d0e5b1ce1b524a50b2a26cfc22bc21d4 = L.marker(
                [55.673776, 12.576675],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_a67866d8309160b3dbdc1f2d0fcaa81c = L.popup({"maxWidth": "100%"});

        
            var html_567004d50e8f8d85febe0ad351386e63 = $(`<div id="html_567004d50e8f8d85febe0ad351386e63" style="width: 100.0%; height: 100.0%;">Year Built: 1769, Price:4.650.000, 88.0 m2 , ZipCode:1472 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_a67866d8309160b3dbdc1f2d0fcaa81c.setContent(html_567004d50e8f8d85febe0ad351386e63);
        

        marker_d0e5b1ce1b524a50b2a26cfc22bc21d4.bindPopup(popup_a67866d8309160b3dbdc1f2d0fcaa81c)
        ;

        
    
    
            var marker_00ceca3691fd15864d1e67f8f00ab746 = L.marker(
                [55.690519, 12.559089],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_db13ecfe61d9b7d167e62f8c38e6a5e2 = L.popup({"maxWidth": "100%"});

        
            var html_32438b983fbdbcd89ea5956b6a8063db = $(`<div id="html_32438b983fbdbcd89ea5956b6a8063db" style="width: 100.0%; height: 100.0%;">Year Built: 1893, Price:3.495.000, 53.0 m2 , ZipCode:2200 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_db13ecfe61d9b7d167e62f8c38e6a5e2.setContent(html_32438b983fbdbcd89ea5956b6a8063db);
        

        marker_00ceca3691fd15864d1e67f8f00ab746.bindPopup(popup_db13ecfe61d9b7d167e62f8c38e6a5e2)
        ;

        
    
    
            var marker_72c32cf4e0977b660df7bcaadf6262a0 = L.marker(
                [55.692286, 12.558562],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_9933df221137be0be1be755b723ffba5 = L.popup({"maxWidth": "100%"});

        
            var html_433751434dba699901fd63c5360d695c = $(`<div id="html_433751434dba699901fd63c5360d695c" style="width: 100.0%; height: 100.0%;">Year Built: 1889, Price:4.999.000, 86.0 m2 , ZipCode:2200 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_9933df221137be0be1be755b723ffba5.setContent(html_433751434dba699901fd63c5360d695c);
        

        marker_72c32cf4e0977b660df7bcaadf6262a0.bindPopup(popup_9933df221137be0be1be755b723ffba5)
        ;

        
    
    
            var marker_d3b93af6996cf36578e7ef819e472fb9 = L.marker(
                [55.702058, 12.549672],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_c6ef0ca0de0c5b785179f18f8ec22fb7 = L.popup({"maxWidth": "100%"});

        
            var html_c3fee1b3cfeea82c7873dbfb3b8e7085 = $(`<div id="html_c3fee1b3cfeea82c7873dbfb3b8e7085" style="width: 100.0%; height: 100.0%;">Year Built: 1902, Price:5.295.000, 131.0 m2 , ZipCode:2200 ,  Rooms:5, HomeType:Ejerlejlighed</div>`)[0];
            popup_c6ef0ca0de0c5b785179f18f8ec22fb7.setContent(html_c3fee1b3cfeea82c7873dbfb3b8e7085);
        

        marker_d3b93af6996cf36578e7ef819e472fb9.bindPopup(popup_c6ef0ca0de0c5b785179f18f8ec22fb7)
        ;

        
    
    
            var marker_009d838568d8fe76d941bd235c4f0242 = L.marker(
                [55.701295, 12.544161],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_5e0fd989d501e52fe9a7dbd1373c4e81 = L.popup({"maxWidth": "100%"});

        
            var html_10d38d1d0b88e9708cab10dc775a6528 = $(`<div id="html_10d38d1d0b88e9708cab10dc775a6528" style="width: 100.0%; height: 100.0%;">Year Built: 1949, Price:2.745.000, 57.0 m2 , ZipCode:2200 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_5e0fd989d501e52fe9a7dbd1373c4e81.setContent(html_10d38d1d0b88e9708cab10dc775a6528);
        

        marker_009d838568d8fe76d941bd235c4f0242.bindPopup(popup_5e0fd989d501e52fe9a7dbd1373c4e81)
        ;

        
    
    
            var marker_1b75aba4cdc436ca75ce625bf7052392 = L.marker(
                [55.703498, 12.548408],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_42c36cd13d203c83aca0b1602cb2ae85 = L.popup({"maxWidth": "100%"});

        
            var html_f05f65339030cde66249ecfd944c94f7 = $(`<div id="html_f05f65339030cde66249ecfd944c94f7" style="width: 100.0%; height: 100.0%;">Year Built: 1908, Price:2.898.000, 62.0 m2 , ZipCode:2200 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_42c36cd13d203c83aca0b1602cb2ae85.setContent(html_f05f65339030cde66249ecfd944c94f7);
        

        marker_1b75aba4cdc436ca75ce625bf7052392.bindPopup(popup_42c36cd13d203c83aca0b1602cb2ae85)
        ;

        
    
    
            var marker_eab0e8136e1239f72a4714c3b094ea03 = L.marker(
                [55.690876, 12.559524],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_c544e80f5d7e2e805e24cb5600ae133e = L.popup({"maxWidth": "100%"});

        
            var html_3bb37b8b9d7946931c6e8081293375e1 = $(`<div id="html_3bb37b8b9d7946931c6e8081293375e1" style="width: 100.0%; height: 100.0%;">Year Built: 1893, Price:2.795.000, 49.0 m2 , ZipCode:2200 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_c544e80f5d7e2e805e24cb5600ae133e.setContent(html_3bb37b8b9d7946931c6e8081293375e1);
        

        marker_eab0e8136e1239f72a4714c3b094ea03.bindPopup(popup_c544e80f5d7e2e805e24cb5600ae133e)
        ;

        
    
    
            var marker_433469ea1c55029927c8b17b84b33a4c = L.marker(
                [55.692023, 12.554434],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_5317f63b225f1e18b817b5ccca922e01 = L.popup({"maxWidth": "100%"});

        
            var html_4e1929c6b1be7cc0bd14fce8a47c0f7a = $(`<div id="html_4e1929c6b1be7cc0bd14fce8a47c0f7a" style="width: 100.0%; height: 100.0%;">Year Built: 1910, Price:2.999.000, 53.0 m2 , ZipCode:2200 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_5317f63b225f1e18b817b5ccca922e01.setContent(html_4e1929c6b1be7cc0bd14fce8a47c0f7a);
        

        marker_433469ea1c55029927c8b17b84b33a4c.bindPopup(popup_5317f63b225f1e18b817b5ccca922e01)
        ;

        
    
    
            var marker_0b31644ab0b2e72c2104e9a88cc9978f = L.marker(
                [55.698437, 12.551921],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_fbfe2f7af39027850594b06bdfac0f0b = L.popup({"maxWidth": "100%"});

        
            var html_59098388c84e6423f7ab32e6801a3932 = $(`<div id="html_59098388c84e6423f7ab32e6801a3932" style="width: 100.0%; height: 100.0%;">Year Built: 1901, Price:4.495.000, 76.0 m2 , ZipCode:2200 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_fbfe2f7af39027850594b06bdfac0f0b.setContent(html_59098388c84e6423f7ab32e6801a3932);
        

        marker_0b31644ab0b2e72c2104e9a88cc9978f.bindPopup(popup_fbfe2f7af39027850594b06bdfac0f0b)
        ;

        
    
    
            var marker_8946651696adf6f6a8d6abf03581ffe3 = L.marker(
                [55.687805, 12.543665],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_c24b613cb5ef405084af83a879dcbd7e = L.popup({"maxWidth": "100%"});

        
            var html_01a76e4a5dc8add22bc7d85a4a9c4cc1 = $(`<div id="html_01a76e4a5dc8add22bc7d85a4a9c4cc1" style="width: 100.0%; height: 100.0%;">Year Built: 1905, Price:5.885.000, 104.0 m2 , ZipCode:2200 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_c24b613cb5ef405084af83a879dcbd7e.setContent(html_01a76e4a5dc8add22bc7d85a4a9c4cc1);
        

        marker_8946651696adf6f6a8d6abf03581ffe3.bindPopup(popup_c24b613cb5ef405084af83a879dcbd7e)
        ;

        
    
    
            var marker_278b65f1c8f18702806e90b5203972d6 = L.marker(
                [55.696152, 12.545833],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_e56542ba21e40649720aab445926c312 = L.popup({"maxWidth": "100%"});

        
            var html_49f87473dc29440a841c9e386ad1fd7c = $(`<div id="html_49f87473dc29440a841c9e386ad1fd7c" style="width: 100.0%; height: 100.0%;">Year Built: 1904, Price:7.799.000, 158.0 m2 , ZipCode:2200 ,  Rooms:6, HomeType:Ejerlejlighed</div>`)[0];
            popup_e56542ba21e40649720aab445926c312.setContent(html_49f87473dc29440a841c9e386ad1fd7c);
        

        marker_278b65f1c8f18702806e90b5203972d6.bindPopup(popup_e56542ba21e40649720aab445926c312)
        ;

        
    
    
            var marker_4194d99317539d541c43f90d72334298 = L.marker(
                [55.693418, 12.545509],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_ba13323da28625e3c84533099a5c9720 = L.popup({"maxWidth": "100%"});

        
            var html_0b4ef45e4f001781dd6d33fccc8f6f00 = $(`<div id="html_0b4ef45e4f001781dd6d33fccc8f6f00" style="width: 100.0%; height: 100.0%;">Year Built: 1901, Price:4.495.000, 70.0 m2 , ZipCode:2200 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_ba13323da28625e3c84533099a5c9720.setContent(html_0b4ef45e4f001781dd6d33fccc8f6f00);
        

        marker_4194d99317539d541c43f90d72334298.bindPopup(popup_ba13323da28625e3c84533099a5c9720)
        ;

        
    
    
            var marker_6090b526573d094d1842469b7bbcb17a = L.marker(
                [55.694629, 12.546446],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_1fd03db2c423217ca6d47ea2b377897f = L.popup({"maxWidth": "100%"});

        
            var html_c75718fb81b09e295ea8bf6fd1f9f4a5 = $(`<div id="html_c75718fb81b09e295ea8bf6fd1f9f4a5" style="width: 100.0%; height: 100.0%;">Year Built: 1903, Price:4.695.000, 82.0 m2 , ZipCode:2200 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_1fd03db2c423217ca6d47ea2b377897f.setContent(html_c75718fb81b09e295ea8bf6fd1f9f4a5);
        

        marker_6090b526573d094d1842469b7bbcb17a.bindPopup(popup_1fd03db2c423217ca6d47ea2b377897f)
        ;

        
    
    
            var marker_16e6de18dd5b4352e190bdbc0cd11baf = L.marker(
                [55.694276, 12.550229],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_00a14896d1d1be854ddc8b90f3be9741 = L.popup({"maxWidth": "100%"});

        
            var html_e6c72ba5627d1767c7551cbe8cfc2af6 = $(`<div id="html_e6c72ba5627d1767c7551cbe8cfc2af6" style="width: 100.0%; height: 100.0%;">Year Built: 1899, Price:3.999.000, 63.0 m2 , ZipCode:2200 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_00a14896d1d1be854ddc8b90f3be9741.setContent(html_e6c72ba5627d1767c7551cbe8cfc2af6);
        

        marker_16e6de18dd5b4352e190bdbc0cd11baf.bindPopup(popup_00a14896d1d1be854ddc8b90f3be9741)
        ;

        
    
    
            var marker_cf3c1349df5845a2291436f2cb05643c = L.marker(
                [55.697419, 12.538743],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_f93d07134ceea945a11088ff88a0cdce = L.popup({"maxWidth": "100%"});

        
            var html_ca95fbbdfffee5ca0985d8031fe52034 = $(`<div id="html_ca95fbbdfffee5ca0985d8031fe52034" style="width: 100.0%; height: 100.0%;">Year Built: 1907, Price:5.195.000, 95.0 m2 , ZipCode:2200 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_f93d07134ceea945a11088ff88a0cdce.setContent(html_ca95fbbdfffee5ca0985d8031fe52034);
        

        marker_cf3c1349df5845a2291436f2cb05643c.bindPopup(popup_f93d07134ceea945a11088ff88a0cdce)
        ;

        
    
    
            var marker_5a367731d1c6f394cca0c658e10e88fc = L.marker(
                [55.701295, 12.544161],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_dcd2968a64e35d882c4758c63c1f75da = L.popup({"maxWidth": "100%"});

        
            var html_732968943b532226850c85a5a18a00b9 = $(`<div id="html_732968943b532226850c85a5a18a00b9" style="width: 100.0%; height: 100.0%;">Year Built: 1949, Price:2.795.000, 54.0 m2 , ZipCode:2200 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_dcd2968a64e35d882c4758c63c1f75da.setContent(html_732968943b532226850c85a5a18a00b9);
        

        marker_5a367731d1c6f394cca0c658e10e88fc.bindPopup(popup_dcd2968a64e35d882c4758c63c1f75da)
        ;

        
    
    
            var marker_a837c52f10e27a86536dd3c1797b521c = L.marker(
                [55.693072, 12.546008],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_e99a9b5de9b8e695edba27b462326232 = L.popup({"maxWidth": "100%"});

        
            var html_c6af2f4f9274154eb9e4c4aa3e1ac645 = $(`<div id="html_c6af2f4f9274154eb9e4c4aa3e1ac645" style="width: 100.0%; height: 100.0%;">Year Built: 1904, Price:4.995.000, 84.0 m2 , ZipCode:2200 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_e99a9b5de9b8e695edba27b462326232.setContent(html_c6af2f4f9274154eb9e4c4aa3e1ac645);
        

        marker_a837c52f10e27a86536dd3c1797b521c.bindPopup(popup_e99a9b5de9b8e695edba27b462326232)
        ;

        
    
    
            var marker_8aff198360870ac882ca7e493314d48e = L.marker(
                [55.692808, 12.56527],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_abe003b831c9174febb5026b40fbe80d = L.popup({"maxWidth": "100%"});

        
            var html_225c1dfd251df8e3b9200527bd266e08 = $(`<div id="html_225c1dfd251df8e3b9200527bd266e08" style="width: 100.0%; height: 100.0%;">Year Built: 1920, Price:5.875.000, 78.0 m2 , ZipCode:2200 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_abe003b831c9174febb5026b40fbe80d.setContent(html_225c1dfd251df8e3b9200527bd266e08);
        

        marker_8aff198360870ac882ca7e493314d48e.bindPopup(popup_abe003b831c9174febb5026b40fbe80d)
        ;

        
    
    
            var marker_63cc283e5a522392f451f86dc9c23e88 = L.marker(
                [55.693221, 12.547348],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_3a4aa2cdea4e2352f21a6df56b1fea2e = L.popup({"maxWidth": "100%"});

        
            var html_25fa9559319312f15718a1e44d805946 = $(`<div id="html_25fa9559319312f15718a1e44d805946" style="width: 100.0%; height: 100.0%;">Year Built: 1906, Price:4.999.000, 90.0 m2 , ZipCode:2200 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_3a4aa2cdea4e2352f21a6df56b1fea2e.setContent(html_25fa9559319312f15718a1e44d805946);
        

        marker_63cc283e5a522392f451f86dc9c23e88.bindPopup(popup_3a4aa2cdea4e2352f21a6df56b1fea2e)
        ;

        
    
    
            var marker_8ceff97aeee0c9837c910281ba0c560d = L.marker(
                [55.698211, 12.543486],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_f15ab8581980afaa837772d229a901c8 = L.popup({"maxWidth": "100%"});

        
            var html_01e1b71573e14e2323b7ca3dd11f2f3c = $(`<div id="html_01e1b71573e14e2323b7ca3dd11f2f3c" style="width: 100.0%; height: 100.0%;">Year Built: 1899, Price:6.995.000, 152.0 m2 , ZipCode:2200 ,  Rooms:5, HomeType:Ejerlejlighed</div>`)[0];
            popup_f15ab8581980afaa837772d229a901c8.setContent(html_01e1b71573e14e2323b7ca3dd11f2f3c);
        

        marker_8ceff97aeee0c9837c910281ba0c560d.bindPopup(popup_f15ab8581980afaa837772d229a901c8)
        ;

        
    
    
            var marker_815c8f48541c2d6bb0e4ccea9eb9a20a = L.marker(
                [55.695465, 12.545101],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_f71cfc0d92385f27515bc56841942b26 = L.popup({"maxWidth": "100%"});

        
            var html_8eeef1b838e8dc129b30d8e519a7900b = $(`<div id="html_8eeef1b838e8dc129b30d8e519a7900b" style="width: 100.0%; height: 100.0%;">Year Built: 1932, Price:3.598.000, 65.0 m2 , ZipCode:2200 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_f71cfc0d92385f27515bc56841942b26.setContent(html_8eeef1b838e8dc129b30d8e519a7900b);
        

        marker_815c8f48541c2d6bb0e4ccea9eb9a20a.bindPopup(popup_f71cfc0d92385f27515bc56841942b26)
        ;

        
    
    
            var marker_ce445a02ddc4ad6e1bdd434db93287e5 = L.marker(
                [55.690497, 12.558023],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_12de66081cde707d6c0cdabaf86ca537 = L.popup({"maxWidth": "100%"});

        
            var html_7dcd74a008bdc28cfa4380a4bdd08fbf = $(`<div id="html_7dcd74a008bdc28cfa4380a4bdd08fbf" style="width: 100.0%; height: 100.0%;">Year Built: 1892, Price:3.145.000, 53.0 m2 , ZipCode:2200 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_12de66081cde707d6c0cdabaf86ca537.setContent(html_7dcd74a008bdc28cfa4380a4bdd08fbf);
        

        marker_ce445a02ddc4ad6e1bdd434db93287e5.bindPopup(popup_12de66081cde707d6c0cdabaf86ca537)
        ;

        
    
    
            var marker_fed81e1718636cd034e434238925c5fd = L.marker(
                [55.705771, 12.551042],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_3d33a5d51fe1597154ca41f9518da86f = L.popup({"maxWidth": "100%"});

        
            var html_19e67db6e3588bf3d5e2695bfcc7aee3 = $(`<div id="html_19e67db6e3588bf3d5e2695bfcc7aee3" style="width: 100.0%; height: 100.0%;">Year Built: 1991, Price:2.650.000, 56.0 m2 , ZipCode:2200 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_3d33a5d51fe1597154ca41f9518da86f.setContent(html_19e67db6e3588bf3d5e2695bfcc7aee3);
        

        marker_fed81e1718636cd034e434238925c5fd.bindPopup(popup_3d33a5d51fe1597154ca41f9518da86f)
        ;

        
    
    
            var marker_b586ad47e2999a4269848b72c12f098f = L.marker(
                [55.695533, 12.545254],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_4a2c3f1ab91805527d55f06fa397e8ee = L.popup({"maxWidth": "100%"});

        
            var html_4b3306be747fc6d0b93c3e9c19e413d7 = $(`<div id="html_4b3306be747fc6d0b93c3e9c19e413d7" style="width: 100.0%; height: 100.0%;">Year Built: 1932, Price:3.295.000, 63.0 m2 , ZipCode:2200 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_4a2c3f1ab91805527d55f06fa397e8ee.setContent(html_4b3306be747fc6d0b93c3e9c19e413d7);
        

        marker_b586ad47e2999a4269848b72c12f098f.bindPopup(popup_4a2c3f1ab91805527d55f06fa397e8ee)
        ;

        
    
    
            var marker_4a2665b04c814e9c48f44b4277fd6602 = L.marker(
                [55.701076, 12.549438],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_895683716ab251d98d3f7ad1b181e2e9 = L.popup({"maxWidth": "100%"});

        
            var html_9c395be3183af8da96b9794b36b723b7 = $(`<div id="html_9c395be3183af8da96b9794b36b723b7" style="width: 100.0%; height: 100.0%;">Year Built: 1902, Price:3.195.000, 58.0 m2 , ZipCode:2200 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_895683716ab251d98d3f7ad1b181e2e9.setContent(html_9c395be3183af8da96b9794b36b723b7);
        

        marker_4a2665b04c814e9c48f44b4277fd6602.bindPopup(popup_895683716ab251d98d3f7ad1b181e2e9)
        ;

        
    
    
            var marker_df4ad90da6d939803446ec8345a6950c = L.marker(
                [55.697556, 12.546515],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_06b5c5dcf0eedb1ae14d6072533da178 = L.popup({"maxWidth": "100%"});

        
            var html_1a82bb29b5c273d5d83a06bbac8b85ae = $(`<div id="html_1a82bb29b5c273d5d83a06bbac8b85ae" style="width: 100.0%; height: 100.0%;">Year Built: 1903, Price:4.999.000, 94.0 m2 , ZipCode:2200 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_06b5c5dcf0eedb1ae14d6072533da178.setContent(html_1a82bb29b5c273d5d83a06bbac8b85ae);
        

        marker_df4ad90da6d939803446ec8345a6950c.bindPopup(popup_06b5c5dcf0eedb1ae14d6072533da178)
        ;

        
    
    
            var marker_3c459f47377285c1e856c346fa903ac9 = L.marker(
                [55.688903, 12.564376],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_94efd508d059824164d0bd03878ec114 = L.popup({"maxWidth": "100%"});

        
            var html_ec930e9e0cbff86cf6614190d9983a6d = $(`<div id="html_ec930e9e0cbff86cf6614190d9983a6d" style="width: 100.0%; height: 100.0%;">Year Built: 1890, Price:6.995.000, 111.0 m2 , ZipCode:2200 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_94efd508d059824164d0bd03878ec114.setContent(html_ec930e9e0cbff86cf6614190d9983a6d);
        

        marker_3c459f47377285c1e856c346fa903ac9.bindPopup(popup_94efd508d059824164d0bd03878ec114)
        ;

        
    
    
            var marker_6c5c138df2db93d64c2a46007896b208 = L.marker(
                [55.692386, 12.558514],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_e3fec8ba54634d66abc394a8fb3d37a6 = L.popup({"maxWidth": "100%"});

        
            var html_e7d7ca2d41a534470757c159782bc87c = $(`<div id="html_e7d7ca2d41a534470757c159782bc87c" style="width: 100.0%; height: 100.0%;">Year Built: 1889, Price:3.050.000, 52.0 m2 , ZipCode:2200 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_e3fec8ba54634d66abc394a8fb3d37a6.setContent(html_e7d7ca2d41a534470757c159782bc87c);
        

        marker_6c5c138df2db93d64c2a46007896b208.bindPopup(popup_e3fec8ba54634d66abc394a8fb3d37a6)
        ;

        
    
    
            var marker_45bfbc247a2032f5fda7760bb1c32e0b = L.marker(
                [55.698183, 12.537568],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_b040b95d0d4e698b6e2d97da3a32a965 = L.popup({"maxWidth": "100%"});

        
            var html_08d92c8618002a4ba0cd6a97524bab62 = $(`<div id="html_08d92c8618002a4ba0cd6a97524bab62" style="width: 100.0%; height: 100.0%;">Year Built: 1930, Price:3.795.000, 70.0 m2 , ZipCode:2200 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_b040b95d0d4e698b6e2d97da3a32a965.setContent(html_08d92c8618002a4ba0cd6a97524bab62);
        

        marker_45bfbc247a2032f5fda7760bb1c32e0b.bindPopup(popup_b040b95d0d4e698b6e2d97da3a32a965)
        ;

        
    
    
            var marker_fe2bf89ea3e7fae51df0be6d36bccac9 = L.marker(
                [55.689278, 12.564866],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_7253e4bdb57305b2a3336dbb722d3581 = L.popup({"maxWidth": "100%"});

        
            var html_1c9a4e0900fa87cf93f63533977c2ac7 = $(`<div id="html_1c9a4e0900fa87cf93f63533977c2ac7" style="width: 100.0%; height: 100.0%;">Year Built: 1892, Price:14.995.000, 184.0 m2 , ZipCode:2200 ,  Rooms:7, HomeType:Ejerlejlighed</div>`)[0];
            popup_7253e4bdb57305b2a3336dbb722d3581.setContent(html_1c9a4e0900fa87cf93f63533977c2ac7);
        

        marker_fe2bf89ea3e7fae51df0be6d36bccac9.bindPopup(popup_7253e4bdb57305b2a3336dbb722d3581)
        ;

        
    
    
            var marker_3544e4cc07ba3fe44608fe990f2411b7 = L.marker(
                [55.695936, 12.544063],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_24bbef4d2fdb0716c5c2e4216c96b670 = L.popup({"maxWidth": "100%"});

        
            var html_99c650356f75884e8793e4d2972020a4 = $(`<div id="html_99c650356f75884e8793e4d2972020a4" style="width: 100.0%; height: 100.0%;">Year Built: 1886, Price:3.395.000, 55.0 m2 , ZipCode:2200 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_24bbef4d2fdb0716c5c2e4216c96b670.setContent(html_99c650356f75884e8793e4d2972020a4);
        

        marker_3544e4cc07ba3fe44608fe990f2411b7.bindPopup(popup_24bbef4d2fdb0716c5c2e4216c96b670)
        ;

        
    
    
            var marker_3ec82ec5edaa93214a67a3e5314005f0 = L.marker(
                [55.696816, 12.540596],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_e8cda7d914f66f9c5f4edb37ccfe447d = L.popup({"maxWidth": "100%"});

        
            var html_ceb7ea92cd42677a2c05742e4735352f = $(`<div id="html_ceb7ea92cd42677a2c05742e4735352f" style="width: 100.0%; height: 100.0%;">Year Built: 1935, Price:2.595.000, 52.0 m2 , ZipCode:2200 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_e8cda7d914f66f9c5f4edb37ccfe447d.setContent(html_ceb7ea92cd42677a2c05742e4735352f);
        

        marker_3ec82ec5edaa93214a67a3e5314005f0.bindPopup(popup_e8cda7d914f66f9c5f4edb37ccfe447d)
        ;

        
    
    
            var marker_1806226563bfbd9fc5ce7d035c56bdb3 = L.marker(
                [55.698804, 12.544487],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_8ebdb1bc7d437a2147f9cb0ad46e84f0 = L.popup({"maxWidth": "100%"});

        
            var html_3075011d88e1ff9b04cc250bdba95c64 = $(`<div id="html_3075011d88e1ff9b04cc250bdba95c64" style="width: 100.0%; height: 100.0%;">Year Built: 1890, Price:4.195.000, 79.0 m2 , ZipCode:2200 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_8ebdb1bc7d437a2147f9cb0ad46e84f0.setContent(html_3075011d88e1ff9b04cc250bdba95c64);
        

        marker_1806226563bfbd9fc5ce7d035c56bdb3.bindPopup(popup_8ebdb1bc7d437a2147f9cb0ad46e84f0)
        ;

        
    
    
            var marker_b26f463c224f9a53bf82cc69355673e7 = L.marker(
                [55.701103, 12.544788],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_55998c358d5bdb4594e4baa51a361cd4 = L.popup({"maxWidth": "100%"});

        
            var html_c0f933e0bf543d2de7d71997918bf7cb = $(`<div id="html_c0f933e0bf543d2de7d71997918bf7cb" style="width: 100.0%; height: 100.0%;">Year Built: 1947, Price:2.995.000, 57.0 m2 , ZipCode:2200 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_55998c358d5bdb4594e4baa51a361cd4.setContent(html_c0f933e0bf543d2de7d71997918bf7cb);
        

        marker_b26f463c224f9a53bf82cc69355673e7.bindPopup(popup_55998c358d5bdb4594e4baa51a361cd4)
        ;

        
    
    
            var marker_c5be80fc1de5871700e74bb203228b90 = L.marker(
                [55.691647, 12.559237],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_eaf6c14bdc25907b38e635091af098bc = L.popup({"maxWidth": "100%"});

        
            var html_da7be2e37d43a0b2edf16ee3fca2b5e5 = $(`<div id="html_da7be2e37d43a0b2edf16ee3fca2b5e5" style="width: 100.0%; height: 100.0%;">Year Built: 1889, Price:2.995.000, 48.0 m2 , ZipCode:2200 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_eaf6c14bdc25907b38e635091af098bc.setContent(html_da7be2e37d43a0b2edf16ee3fca2b5e5);
        

        marker_c5be80fc1de5871700e74bb203228b90.bindPopup(popup_eaf6c14bdc25907b38e635091af098bc)
        ;

        
    
    
            var marker_999887ce29eddfc891dc1897009e03b3 = L.marker(
                [55.696453, 12.546127],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_e777ad3e78589e7f7ec6f235712fa011 = L.popup({"maxWidth": "100%"});

        
            var html_4124b3e5d65b4384cbb9b72856762dde = $(`<div id="html_4124b3e5d65b4384cbb9b72856762dde" style="width: 100.0%; height: 100.0%;">Year Built: 1990, Price:4.650.000, 97.0 m2 , ZipCode:2200 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_e777ad3e78589e7f7ec6f235712fa011.setContent(html_4124b3e5d65b4384cbb9b72856762dde);
        

        marker_999887ce29eddfc891dc1897009e03b3.bindPopup(popup_e777ad3e78589e7f7ec6f235712fa011)
        ;

        
    
    
            var marker_4f1bc3b16f87649ece0d711823bb16da = L.marker(
                [55.697556, 12.546515],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_1a107b9c14b90d36d13e23c3b08e58b6 = L.popup({"maxWidth": "100%"});

        
            var html_3dcb57dc685979a4c209e25bf462a05c = $(`<div id="html_3dcb57dc685979a4c209e25bf462a05c" style="width: 100.0%; height: 100.0%;">Year Built: 1903, Price:4.950.000, 94.0 m2 , ZipCode:2200 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_1a107b9c14b90d36d13e23c3b08e58b6.setContent(html_3dcb57dc685979a4c209e25bf462a05c);
        

        marker_4f1bc3b16f87649ece0d711823bb16da.bindPopup(popup_1a107b9c14b90d36d13e23c3b08e58b6)
        ;

        
    
    
            var marker_719825915c88a2a16d3ca8f5775a5d85 = L.marker(
                [55.692028, 12.558795],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_ae32f6f248a88281c4d6c1960affaace = L.popup({"maxWidth": "100%"});

        
            var html_5681c7bc50f786bc192172d5ba9448c1 = $(`<div id="html_5681c7bc50f786bc192172d5ba9448c1" style="width: 100.0%; height: 100.0%;">Year Built: 1860, Price:3.198.000, 50.0 m2 , ZipCode:2200 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_ae32f6f248a88281c4d6c1960affaace.setContent(html_5681c7bc50f786bc192172d5ba9448c1);
        

        marker_719825915c88a2a16d3ca8f5775a5d85.bindPopup(popup_ae32f6f248a88281c4d6c1960affaace)
        ;

        
    
    
            var marker_1d3bc5420dd272a1f7e9843e208bc968 = L.marker(
                [55.690497, 12.558023],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_d10900f22399e20ca36a47661a1958fb = L.popup({"maxWidth": "100%"});

        
            var html_08ea80bd5760a9d82203bb6c3c8a82b0 = $(`<div id="html_08ea80bd5760a9d82203bb6c3c8a82b0" style="width: 100.0%; height: 100.0%;">Year Built: 1892, Price:3.475.000, 46.0 m2 , ZipCode:2200 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_d10900f22399e20ca36a47661a1958fb.setContent(html_08ea80bd5760a9d82203bb6c3c8a82b0);
        

        marker_1d3bc5420dd272a1f7e9843e208bc968.bindPopup(popup_d10900f22399e20ca36a47661a1958fb)
        ;

        
    
    
            var marker_8e7d1e17355ae137fdb9dec42ba0f356 = L.marker(
                [55.701295, 12.544161],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_19801f32c2d0b7ceca947960e4018cb8 = L.popup({"maxWidth": "100%"});

        
            var html_0c7955199646d89418a2b052a4d9755f = $(`<div id="html_0c7955199646d89418a2b052a4d9755f" style="width: 100.0%; height: 100.0%;">Year Built: 1949, Price:2.295.000, 54.0 m2 , ZipCode:2200 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_19801f32c2d0b7ceca947960e4018cb8.setContent(html_0c7955199646d89418a2b052a4d9755f);
        

        marker_8e7d1e17355ae137fdb9dec42ba0f356.bindPopup(popup_19801f32c2d0b7ceca947960e4018cb8)
        ;

        
    
    
            var marker_bd288adbb345c4594603476114ca2b7f = L.marker(
                [55.692535, 12.543486],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_b8c6e62c57c23032e472c3571c4ed0d4 = L.popup({"maxWidth": "100%"});

        
            var html_c83b0e40f31d79f566830b33582cc8cd = $(`<div id="html_c83b0e40f31d79f566830b33582cc8cd" style="width: 100.0%; height: 100.0%;">Year Built: 1900, Price:4.250.000, 65.0 m2 , ZipCode:2200 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_b8c6e62c57c23032e472c3571c4ed0d4.setContent(html_c83b0e40f31d79f566830b33582cc8cd);
        

        marker_bd288adbb345c4594603476114ca2b7f.bindPopup(popup_b8c6e62c57c23032e472c3571c4ed0d4)
        ;

        
    
    
            var marker_0bbb0c1b1bb2461c365a92e91949f737 = L.marker(
                [55.698183, 12.537568],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_e9bf60b33b2a81386cee7e7043684e24 = L.popup({"maxWidth": "100%"});

        
            var html_5c4c9cfaf7fa90adf2efff5f4e04f977 = $(`<div id="html_5c4c9cfaf7fa90adf2efff5f4e04f977" style="width: 100.0%; height: 100.0%;">Year Built: 1930, Price:3.995.000, 75.0 m2 , ZipCode:2200 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_e9bf60b33b2a81386cee7e7043684e24.setContent(html_5c4c9cfaf7fa90adf2efff5f4e04f977);
        

        marker_0bbb0c1b1bb2461c365a92e91949f737.bindPopup(popup_e9bf60b33b2a81386cee7e7043684e24)
        ;

        
    
    
            var marker_85f7b69d3c0842f44f43716ea94e16ab = L.marker(
                [55.700936, 12.550414],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_86c36938298460bf6d1ca4872a8f203b = L.popup({"maxWidth": "100%"});

        
            var html_7e92c8f4a140398b215597fa28149a1d = $(`<div id="html_7e92c8f4a140398b215597fa28149a1d" style="width: 100.0%; height: 100.0%;">Year Built: 1907, Price:2.995.000, 58.0 m2 , ZipCode:2200 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_86c36938298460bf6d1ca4872a8f203b.setContent(html_7e92c8f4a140398b215597fa28149a1d);
        

        marker_85f7b69d3c0842f44f43716ea94e16ab.bindPopup(popup_86c36938298460bf6d1ca4872a8f203b)
        ;

        
    
    
            var marker_f4dea6f0b31dec31797655bc7c744ee8 = L.marker(
                [55.694508, 12.54655],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_2577988486765613726b161c804106c0 = L.popup({"maxWidth": "100%"});

        
            var html_c15d80a2a9657e2f23f8f7150887b601 = $(`<div id="html_c15d80a2a9657e2f23f8f7150887b601" style="width: 100.0%; height: 100.0%;">Year Built: 1903, Price:4.395.000, 72.0 m2 , ZipCode:2200 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_2577988486765613726b161c804106c0.setContent(html_c15d80a2a9657e2f23f8f7150887b601);
        

        marker_f4dea6f0b31dec31797655bc7c744ee8.bindPopup(popup_2577988486765613726b161c804106c0)
        ;

        
    
    
            var marker_ae750f5adb362d12a49d74d1409afd37 = L.marker(
                [55.698716, 12.551086],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_3e37396697638e41a4fdadd5c8408321 = L.popup({"maxWidth": "100%"});

        
            var html_0e803983f61a5857ac321762c0976de6 = $(`<div id="html_0e803983f61a5857ac321762c0976de6" style="width: 100.0%; height: 100.0%;">Year Built: 1906, Price:4.250.000, 79.0 m2 , ZipCode:2200 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_3e37396697638e41a4fdadd5c8408321.setContent(html_0e803983f61a5857ac321762c0976de6);
        

        marker_ae750f5adb362d12a49d74d1409afd37.bindPopup(popup_3e37396697638e41a4fdadd5c8408321)
        ;

        
    
    
            var marker_5af361da9bbb7f19ba4628a69b2c4d08 = L.marker(
                [55.689424, 12.565064],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_463703fdd161c8f7e6eed2d2827b43fc = L.popup({"maxWidth": "100%"});

        
            var html_f5eba1a171217138fcb65e4af930b844 = $(`<div id="html_f5eba1a171217138fcb65e4af930b844" style="width: 100.0%; height: 100.0%;">Year Built: 1892, Price:13.995.000, 155.0 m2 , ZipCode:2200 ,  Rooms:6, HomeType:Ejerlejlighed</div>`)[0];
            popup_463703fdd161c8f7e6eed2d2827b43fc.setContent(html_f5eba1a171217138fcb65e4af930b844);
        

        marker_5af361da9bbb7f19ba4628a69b2c4d08.bindPopup(popup_463703fdd161c8f7e6eed2d2827b43fc)
        ;

        
    
    
            var marker_4456ec7de16dcd62648bfe200fa36ba9 = L.marker(
                [55.692068, 12.55865],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_d9fea866459abf33fc390c5e3dd8f4cd = L.popup({"maxWidth": "100%"});

        
            var html_24335a1b0d1ea2cc990786e1847c135c = $(`<div id="html_24335a1b0d1ea2cc990786e1847c135c" style="width: 100.0%; height: 100.0%;">Year Built: 1889, Price:2.548.000, 50.0 m2 , ZipCode:2200 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_d9fea866459abf33fc390c5e3dd8f4cd.setContent(html_24335a1b0d1ea2cc990786e1847c135c);
        

        marker_4456ec7de16dcd62648bfe200fa36ba9.bindPopup(popup_d9fea866459abf33fc390c5e3dd8f4cd)
        ;

        
    
    
            var marker_0bdd7e9d69b8f9cc95bd42e9df83220d = L.marker(
                [55.686913, 12.544003],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_ee2234a1136ddb0e14691aa07872ec92 = L.popup({"maxWidth": "100%"});

        
            var html_f15acb5da52e5287430f18189e70207a = $(`<div id="html_f15acb5da52e5287430f18189e70207a" style="width: 100.0%; height: 100.0%;">Year Built: 1899, Price:4.000.000, 82.0 m2 , ZipCode:2200 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_ee2234a1136ddb0e14691aa07872ec92.setContent(html_f15acb5da52e5287430f18189e70207a);
        

        marker_0bdd7e9d69b8f9cc95bd42e9df83220d.bindPopup(popup_ee2234a1136ddb0e14691aa07872ec92)
        ;

        
    
    
            var marker_98770970a047edce9a2813599b0c00fe = L.marker(
                [55.693418, 12.545509],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_3c5edfcdb461a80be41fc474a7d46c38 = L.popup({"maxWidth": "100%"});

        
            var html_e3b1dbb7468b2bbe49e546561b8187a3 = $(`<div id="html_e3b1dbb7468b2bbe49e546561b8187a3" style="width: 100.0%; height: 100.0%;">Year Built: 1901, Price:4.299.000, 70.0 m2 , ZipCode:2200 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_3c5edfcdb461a80be41fc474a7d46c38.setContent(html_e3b1dbb7468b2bbe49e546561b8187a3);
        

        marker_98770970a047edce9a2813599b0c00fe.bindPopup(popup_3c5edfcdb461a80be41fc474a7d46c38)
        ;

        
    
    
            var marker_2f488d66963e90ec54b72a2999d06d5f = L.marker(
                [55.68812, 12.541327],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_3c770fdb4d8cb4d32ee7d8b0bedb44e0 = L.popup({"maxWidth": "100%"});

        
            var html_3dba737a24bcdfe28f61488bd5854fde = $(`<div id="html_3dba737a24bcdfe28f61488bd5854fde" style="width: 100.0%; height: 100.0%;">Year Built: 1906, Price:5.995.000, 145.0 m2 , ZipCode:2200 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_3c770fdb4d8cb4d32ee7d8b0bedb44e0.setContent(html_3dba737a24bcdfe28f61488bd5854fde);
        

        marker_2f488d66963e90ec54b72a2999d06d5f.bindPopup(popup_3c770fdb4d8cb4d32ee7d8b0bedb44e0)
        ;

        
    
    
            var marker_d474fceb6ca41f7baa5113f165b1e013 = L.marker(
                [55.697043, 12.540226],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_6aa1fc46319a3a3615bc67dfa5eec61c = L.popup({"maxWidth": "100%"});

        
            var html_322c5e970e50fec4d94a3c65e0fb397e = $(`<div id="html_322c5e970e50fec4d94a3c65e0fb397e" style="width: 100.0%; height: 100.0%;">Year Built: 1935, Price:2.595.000, 53.0 m2 , ZipCode:2200 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_6aa1fc46319a3a3615bc67dfa5eec61c.setContent(html_322c5e970e50fec4d94a3c65e0fb397e);
        

        marker_d474fceb6ca41f7baa5113f165b1e013.bindPopup(popup_6aa1fc46319a3a3615bc67dfa5eec61c)
        ;

        
    
    
            var marker_a276b692ce20b551467a4f654c6cd521 = L.marker(
                [55.697595, 12.540016],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_486d1b9ba940d9d0f64721c6b455bdbf = L.popup({"maxWidth": "100%"});

        
            var html_9d8cd0c1776b870d7b224a61a766829a = $(`<div id="html_9d8cd0c1776b870d7b224a61a766829a" style="width: 100.0%; height: 100.0%;">Year Built: 1904, Price:2.799.000, 50.0 m2 , ZipCode:2200 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_486d1b9ba940d9d0f64721c6b455bdbf.setContent(html_9d8cd0c1776b870d7b224a61a766829a);
        

        marker_a276b692ce20b551467a4f654c6cd521.bindPopup(popup_486d1b9ba940d9d0f64721c6b455bdbf)
        ;

        
    
    
            var marker_bce6ccafb5d42094a0754dacacc7bd96 = L.marker(
                [55.699835, 12.54079],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_a5069e27e9bd926ed0dec148c38dafc0 = L.popup({"maxWidth": "100%"});

        
            var html_bfd85564f3f9879d8c77e83579e0dde3 = $(`<div id="html_bfd85564f3f9879d8c77e83579e0dde3" style="width: 100.0%; height: 100.0%;">Year Built: 1905, Price:6.995.000, 121.0 m2 , ZipCode:2200 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_a5069e27e9bd926ed0dec148c38dafc0.setContent(html_bfd85564f3f9879d8c77e83579e0dde3);
        

        marker_bce6ccafb5d42094a0754dacacc7bd96.bindPopup(popup_a5069e27e9bd926ed0dec148c38dafc0)
        ;

        
    
    
            var marker_c4bd3f6681893187e4433b96dba969ac = L.marker(
                [55.697839, 12.542289],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_affee5670f77d5f295999baa0faed418 = L.popup({"maxWidth": "100%"});

        
            var html_2c267333aaa06d70eeb35603f03793c8 = $(`<div id="html_2c267333aaa06d70eeb35603f03793c8" style="width: 100.0%; height: 100.0%;">Year Built: 1915, Price:2.795.000, 58.0 m2 , ZipCode:2200 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_affee5670f77d5f295999baa0faed418.setContent(html_2c267333aaa06d70eeb35603f03793c8);
        

        marker_c4bd3f6681893187e4433b96dba969ac.bindPopup(popup_affee5670f77d5f295999baa0faed418)
        ;

        
    
    
            var marker_fceacd82e96ae4073179c2f7d5897940 = L.marker(
                [55.707022, 12.537118],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_505c4af5a3d0a83dd4a77165273837fa = L.popup({"maxWidth": "100%"});

        
            var html_79fde53b95dd8dc5d6691574052a2ced = $(`<div id="html_79fde53b95dd8dc5d6691574052a2ced" style="width: 100.0%; height: 100.0%;">Year Built: 1937, Price:2.195.000, 45.0 m2 , ZipCode:2400 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_505c4af5a3d0a83dd4a77165273837fa.setContent(html_79fde53b95dd8dc5d6691574052a2ced);
        

        marker_fceacd82e96ae4073179c2f7d5897940.bindPopup(popup_505c4af5a3d0a83dd4a77165273837fa)
        ;

        
    
    
            var marker_a3b2b07f6e70cd26f8e98f6586343790 = L.marker(
                [55.706059, 12.528552],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_63ba966ea03652825f925608fcdb67c6 = L.popup({"maxWidth": "100%"});

        
            var html_018bb789b4420052fb42ec094edd4d96 = $(`<div id="html_018bb789b4420052fb42ec094edd4d96" style="width: 100.0%; height: 100.0%;">Year Built: 1897, Price:2.175.000, 48.0 m2 , ZipCode:2400 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_63ba966ea03652825f925608fcdb67c6.setContent(html_018bb789b4420052fb42ec094edd4d96);
        

        marker_a3b2b07f6e70cd26f8e98f6586343790.bindPopup(popup_63ba966ea03652825f925608fcdb67c6)
        ;

        
    
    
            var marker_84e27d75c5e88545d4df50248493bf9a = L.marker(
                [55.721731, 12.525875],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_ed82dbe1eb7bb90f46209de28520803e = L.popup({"maxWidth": "100%"});

        
            var html_0b70a87b241b44c4383f27541838de2a = $(`<div id="html_0b70a87b241b44c4383f27541838de2a" style="width: 100.0%; height: 100.0%;">Year Built: 1938, Price:2.695.000, 58.0 m2 , ZipCode:2400 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_ed82dbe1eb7bb90f46209de28520803e.setContent(html_0b70a87b241b44c4383f27541838de2a);
        

        marker_84e27d75c5e88545d4df50248493bf9a.bindPopup(popup_ed82dbe1eb7bb90f46209de28520803e)
        ;

        
    
    
            var marker_95e3faa378540b7ec0056cd5944b3742 = L.marker(
                [55.704465, 12.527165],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_ebebd009cb0138c31efd8d9901932f8e = L.popup({"maxWidth": "100%"});

        
            var html_63b4d9b8641780fa2dea55e05a40bd19 = $(`<div id="html_63b4d9b8641780fa2dea55e05a40bd19" style="width: 100.0%; height: 100.0%;">Year Built: 1932, Price:3.200.000, 76.0 m2 , ZipCode:2400 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_ebebd009cb0138c31efd8d9901932f8e.setContent(html_63b4d9b8641780fa2dea55e05a40bd19);
        

        marker_95e3faa378540b7ec0056cd5944b3742.bindPopup(popup_ebebd009cb0138c31efd8d9901932f8e)
        ;

        
    
    
            var marker_f6a4cd63abb6730a61a8af4b49a2c976 = L.marker(
                [55.702097, 12.529552],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_cb3c3a9fc28883ef0a7aaa622f289662 = L.popup({"maxWidth": "100%"});

        
            var html_302c823918ceab84002477d175aefe0d = $(`<div id="html_302c823918ceab84002477d175aefe0d" style="width: 100.0%; height: 100.0%;">Year Built: 1925, Price:3.695.000, 75.0 m2 , ZipCode:2400 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_cb3c3a9fc28883ef0a7aaa622f289662.setContent(html_302c823918ceab84002477d175aefe0d);
        

        marker_f6a4cd63abb6730a61a8af4b49a2c976.bindPopup(popup_cb3c3a9fc28883ef0a7aaa622f289662)
        ;

        
    
    
            var marker_3fdc872a789d56fc8994c488dccb5218 = L.marker(
                [55.699783, 12.529093],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_79750f0330904d3d4ea19c51e5d00e23 = L.popup({"maxWidth": "100%"});

        
            var html_9af45175e9b75070492ffb6df8e73c5e = $(`<div id="html_9af45175e9b75070492ffb6df8e73c5e" style="width: 100.0%; height: 100.0%;">Year Built: 1937, Price:1.848.000, 56.0 m2 , ZipCode:2400 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_79750f0330904d3d4ea19c51e5d00e23.setContent(html_9af45175e9b75070492ffb6df8e73c5e);
        

        marker_3fdc872a789d56fc8994c488dccb5218.bindPopup(popup_79750f0330904d3d4ea19c51e5d00e23)
        ;

        
    
    
            var marker_d4881867f853b48ff5e8bc0290c07753 = L.marker(
                [55.706102, 12.533247],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_58cccb48d6f144711fa8efadb03e8be0 = L.popup({"maxWidth": "100%"});

        
            var html_c424bcd6ac6a2d4d8bd9eb95e43e63f7 = $(`<div id="html_c424bcd6ac6a2d4d8bd9eb95e43e63f7" style="width: 100.0%; height: 100.0%;">Year Built: 1935, Price:2.195.000, 54.0 m2 , ZipCode:2400 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_58cccb48d6f144711fa8efadb03e8be0.setContent(html_c424bcd6ac6a2d4d8bd9eb95e43e63f7);
        

        marker_d4881867f853b48ff5e8bc0290c07753.bindPopup(popup_58cccb48d6f144711fa8efadb03e8be0)
        ;

        
    
    
            var marker_b1d0744b417fca6473216f40613b35e4 = L.marker(
                [55.708858, 12.529899],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_64310e55c3152f2e7b5636e2d23bc776 = L.popup({"maxWidth": "100%"});

        
            var html_10bed5195dac045877bd50ba19c141b1 = $(`<div id="html_10bed5195dac045877bd50ba19c141b1" style="width: 100.0%; height: 100.0%;">Year Built: 1934, Price:2.395.000, 61.0 m2 , ZipCode:2400 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_64310e55c3152f2e7b5636e2d23bc776.setContent(html_10bed5195dac045877bd50ba19c141b1);
        

        marker_b1d0744b417fca6473216f40613b35e4.bindPopup(popup_64310e55c3152f2e7b5636e2d23bc776)
        ;

        
    
    
            var marker_5823d1205780a11c11ebb46e568d610e = L.marker(
                [55.699458, 12.521923],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_90fbe56dd7aa7bd22be43c9214537f72 = L.popup({"maxWidth": "100%"});

        
            var html_639c0611fa1328625cccdeb9f7c53021 = $(`<div id="html_639c0611fa1328625cccdeb9f7c53021" style="width: 100.0%; height: 100.0%;">Year Built: 1928, Price:2.495.000, 65.0 m2 , ZipCode:2400 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_90fbe56dd7aa7bd22be43c9214537f72.setContent(html_639c0611fa1328625cccdeb9f7c53021);
        

        marker_5823d1205780a11c11ebb46e568d610e.bindPopup(popup_90fbe56dd7aa7bd22be43c9214537f72)
        ;

        
    
    
            var marker_b0d2857a7c3f7d88a1b64382598a44d4 = L.marker(
                [55.704851, 12.532796],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_067e36260f77b737016bf08cad23d109 = L.popup({"maxWidth": "100%"});

        
            var html_4a7f3898ac950d5cd16f22a73999879f = $(`<div id="html_4a7f3898ac950d5cd16f22a73999879f" style="width: 100.0%; height: 100.0%;">Year Built: 2006, Price:4.995.000, 102.0 m2 , ZipCode:2400 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_067e36260f77b737016bf08cad23d109.setContent(html_4a7f3898ac950d5cd16f22a73999879f);
        

        marker_b0d2857a7c3f7d88a1b64382598a44d4.bindPopup(popup_067e36260f77b737016bf08cad23d109)
        ;

        
    
    
            var marker_de956cfa1e1ab92479830b36bd889f64 = L.marker(
                [55.70262, 12.533603],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_e24f1ad9a33c9b83476809a02f3ff76c = L.popup({"maxWidth": "100%"});

        
            var html_fbfcd0f3199356cdfb4f70edc298ad70 = $(`<div id="html_fbfcd0f3199356cdfb4f70edc298ad70" style="width: 100.0%; height: 100.0%;">Year Built: 1940, Price:2.495.000, 57.0 m2 , ZipCode:2400 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_e24f1ad9a33c9b83476809a02f3ff76c.setContent(html_fbfcd0f3199356cdfb4f70edc298ad70);
        

        marker_de956cfa1e1ab92479830b36bd889f64.bindPopup(popup_e24f1ad9a33c9b83476809a02f3ff76c)
        ;

        
    
    
            var marker_6fadb6e286dbfa1935c2c32f87e712c4 = L.marker(
                [55.707721, 12.538705],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_e304af5b7c0cb89a14713513b428d6cd = L.popup({"maxWidth": "100%"});

        
            var html_3b28aa10de1cb129ddb3726654193358 = $(`<div id="html_3b28aa10de1cb129ddb3726654193358" style="width: 100.0%; height: 100.0%;">Year Built: 1938, Price:3.795.000, 97.0 m2 , ZipCode:2400 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_e304af5b7c0cb89a14713513b428d6cd.setContent(html_3b28aa10de1cb129ddb3726654193358);
        

        marker_6fadb6e286dbfa1935c2c32f87e712c4.bindPopup(popup_e304af5b7c0cb89a14713513b428d6cd)
        ;

        
    
    
            var marker_42e82a7caf603e92c0d968c5a52e478b = L.marker(
                [55.704461, 12.52734],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_ae0a870d99fec730dfb2c5fa9c34296d = L.popup({"maxWidth": "100%"});

        
            var html_9d4b091b3b83445ba0fed7832fbbcbd9 = $(`<div id="html_9d4b091b3b83445ba0fed7832fbbcbd9" style="width: 100.0%; height: 100.0%;">Year Built: 1932, Price:2.150.000, 45.0 m2 , ZipCode:2400 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_ae0a870d99fec730dfb2c5fa9c34296d.setContent(html_9d4b091b3b83445ba0fed7832fbbcbd9);
        

        marker_42e82a7caf603e92c0d968c5a52e478b.bindPopup(popup_ae0a870d99fec730dfb2c5fa9c34296d)
        ;

        
    
    
            var marker_314087cd698ba53309a88d3dec49190f = L.marker(
                [55.705267, 12.525357],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_0895f7258685cb98baeceeaf846fa23e = L.popup({"maxWidth": "100%"});

        
            var html_f6cf124fdc12b646746df624d660ad4e = $(`<div id="html_f6cf124fdc12b646746df624d660ad4e" style="width: 100.0%; height: 100.0%;">Year Built: 1974, Price:1.595.000, 41.0 m2 , ZipCode:2400 ,  Rooms:1, HomeType:Ejerlejlighed</div>`)[0];
            popup_0895f7258685cb98baeceeaf846fa23e.setContent(html_f6cf124fdc12b646746df624d660ad4e);
        

        marker_314087cd698ba53309a88d3dec49190f.bindPopup(popup_0895f7258685cb98baeceeaf846fa23e)
        ;

        
    
    
            var marker_158e1652406c07ea0e85186cfe0e0ade = L.marker(
                [55.698876, 12.530247],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_7d0cad050a36920ff7a67b340c80c13d = L.popup({"maxWidth": "100%"});

        
            var html_27b48a38253483a6ee86af208aa821a0 = $(`<div id="html_27b48a38253483a6ee86af208aa821a0" style="width: 100.0%; height: 100.0%;">Year Built: 1936, Price:3.495.000, 80.0 m2 , ZipCode:2400 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_7d0cad050a36920ff7a67b340c80c13d.setContent(html_27b48a38253483a6ee86af208aa821a0);
        

        marker_158e1652406c07ea0e85186cfe0e0ade.bindPopup(popup_7d0cad050a36920ff7a67b340c80c13d)
        ;

        
    
    
            var marker_80fa3b4d5d717851fad6820c15386aaa = L.marker(
                [55.7014, 12.531094],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_4edde74dc76ddc6dc2521025312c9e1d = L.popup({"maxWidth": "100%"});

        
            var html_6031667f53d24d83c871920964a148ea = $(`<div id="html_6031667f53d24d83c871920964a148ea" style="width: 100.0%; height: 100.0%;">Year Built: 1936, Price:1.795.000, 40.0 m2 , ZipCode:2400 ,  Rooms:1, HomeType:Ejerlejlighed</div>`)[0];
            popup_4edde74dc76ddc6dc2521025312c9e1d.setContent(html_6031667f53d24d83c871920964a148ea);
        

        marker_80fa3b4d5d717851fad6820c15386aaa.bindPopup(popup_4edde74dc76ddc6dc2521025312c9e1d)
        ;

        
    
    
            var marker_584777386fe9900b5ced6c8b6c98dbd6 = L.marker(
                [55.722965, 12.535302],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_de7fe8b312adb5f0c93f5c24160d8552 = L.popup({"maxWidth": "100%"});

        
            var html_86c2c244ae4f426870ce78730d9ed094 = $(`<div id="html_86c2c244ae4f426870ce78730d9ed094" style="width: 100.0%; height: 100.0%;">Year Built: 1952, Price:3.595.000, 90.0 m2 , ZipCode:2400 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_de7fe8b312adb5f0c93f5c24160d8552.setContent(html_86c2c244ae4f426870ce78730d9ed094);
        

        marker_584777386fe9900b5ced6c8b6c98dbd6.bindPopup(popup_de7fe8b312adb5f0c93f5c24160d8552)
        ;

        
    
    
            var marker_d995828758dc8ccafff13adaf8af0371 = L.marker(
                [55.710873, 12.515984],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_63df781b6ca45718730516f02039bc93 = L.popup({"maxWidth": "100%"});

        
            var html_00d692d4dcba303d40687c02daee4466 = $(`<div id="html_00d692d4dcba303d40687c02daee4466" style="width: 100.0%; height: 100.0%;">Year Built: 1956, Price:2.995.000, 91.0 m2 , ZipCode:2400 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_63df781b6ca45718730516f02039bc93.setContent(html_00d692d4dcba303d40687c02daee4466);
        

        marker_d995828758dc8ccafff13adaf8af0371.bindPopup(popup_63df781b6ca45718730516f02039bc93)
        ;

        
    
    
            var marker_68e8813bec315a58f6617066e08b691a = L.marker(
                [55.706697, 12.536076],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_3072c36c44636910c04ed59189f28e8b = L.popup({"maxWidth": "100%"});

        
            var html_e965748531e7f599475b887d4f799a48 = $(`<div id="html_e965748531e7f599475b887d4f799a48" style="width: 100.0%; height: 100.0%;">Year Built: 1935, Price:1.999.000, 50.0 m2 , ZipCode:2400 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_3072c36c44636910c04ed59189f28e8b.setContent(html_e965748531e7f599475b887d4f799a48);
        

        marker_68e8813bec315a58f6617066e08b691a.bindPopup(popup_3072c36c44636910c04ed59189f28e8b)
        ;

        
    
    
            var marker_e141087ea4251c1856a95dd3205d6ab7 = L.marker(
                [55.708479, 12.530305],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_057a38472762cf789d36120929c89069 = L.popup({"maxWidth": "100%"});

        
            var html_080b05375714e5bfcc87bdd0c2a73389 = $(`<div id="html_080b05375714e5bfcc87bdd0c2a73389" style="width: 100.0%; height: 100.0%;">Year Built: 1933, Price:2.295.000, 47.0 m2 , ZipCode:2400 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_057a38472762cf789d36120929c89069.setContent(html_080b05375714e5bfcc87bdd0c2a73389);
        

        marker_e141087ea4251c1856a95dd3205d6ab7.bindPopup(popup_057a38472762cf789d36120929c89069)
        ;

        
    
    
            var marker_e9baf55266af730fed64e5a9d90aeffb = L.marker(
                [55.708861, 12.529492],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_9a78bc6efddc1fab364875a665889a55 = L.popup({"maxWidth": "100%"});

        
            var html_0faeb1a1fe51e647baa9fcd582c3438c = $(`<div id="html_0faeb1a1fe51e647baa9fcd582c3438c" style="width: 100.0%; height: 100.0%;">Year Built: 1934, Price:2.795.000, 75.0 m2 , ZipCode:2400 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_9a78bc6efddc1fab364875a665889a55.setContent(html_0faeb1a1fe51e647baa9fcd582c3438c);
        

        marker_e9baf55266af730fed64e5a9d90aeffb.bindPopup(popup_9a78bc6efddc1fab364875a665889a55)
        ;

        
    
    
            var marker_1230d5ab845bf2212d9094617944e661 = L.marker(
                [55.699458, 12.521923],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_089e2434bb02ca3e0943c468ed8711b8 = L.popup({"maxWidth": "100%"});

        
            var html_faa0e6193fdb40d3c264c71757e43d27 = $(`<div id="html_faa0e6193fdb40d3c264c71757e43d27" style="width: 100.0%; height: 100.0%;">Year Built: 1928, Price:4.595.000, 122.0 m2 , ZipCode:2400 ,  Rooms:5, HomeType:Ejerlejlighed</div>`)[0];
            popup_089e2434bb02ca3e0943c468ed8711b8.setContent(html_faa0e6193fdb40d3c264c71757e43d27);
        

        marker_1230d5ab845bf2212d9094617944e661.bindPopup(popup_089e2434bb02ca3e0943c468ed8711b8)
        ;

        
    
    
            var marker_bc940f68ce54788ac7d9346c0b052526 = L.marker(
                [55.721747, 12.526026],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_f91b90263d1b75efe00ae635ab40e5ec = L.popup({"maxWidth": "100%"});

        
            var html_befe7866972288cf4c1f6e8902b71461 = $(`<div id="html_befe7866972288cf4c1f6e8902b71461" style="width: 100.0%; height: 100.0%;">Year Built: 1938, Price:1.495.000, 35.0 m2 , ZipCode:2400 ,  Rooms:1, HomeType:Ejerlejlighed</div>`)[0];
            popup_f91b90263d1b75efe00ae635ab40e5ec.setContent(html_befe7866972288cf4c1f6e8902b71461);
        

        marker_bc940f68ce54788ac7d9346c0b052526.bindPopup(popup_f91b90263d1b75efe00ae635ab40e5ec)
        ;

        
    
    
            var marker_335fc5c214ccfb0d082781049b6670a0 = L.marker(
                [55.699458, 12.521923],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_e798307a6b28e0408c8314c1c4b1014d = L.popup({"maxWidth": "100%"});

        
            var html_a50b86910637e6d220e4a22c327b647d = $(`<div id="html_a50b86910637e6d220e4a22c327b647d" style="width: 100.0%; height: 100.0%;">Year Built: 1928, Price:2.345.000, 64.0 m2 , ZipCode:2400 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_e798307a6b28e0408c8314c1c4b1014d.setContent(html_a50b86910637e6d220e4a22c327b647d);
        

        marker_335fc5c214ccfb0d082781049b6670a0.bindPopup(popup_e798307a6b28e0408c8314c1c4b1014d)
        ;

        
    
    
            var marker_f21a8db913c7ec1d93d64ebaa54dc1b7 = L.marker(
                [55.700604, 12.520528],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_a9af7f7bb2bb2b7703d4866f67cc8e4d = L.popup({"maxWidth": "100%"});

        
            var html_51c7ac624dc594bbbb1674a13176aa47 = $(`<div id="html_51c7ac624dc594bbbb1674a13176aa47" style="width: 100.0%; height: 100.0%;">Year Built: 1921, Price:2.695.000, 64.0 m2 , ZipCode:2400 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_a9af7f7bb2bb2b7703d4866f67cc8e4d.setContent(html_51c7ac624dc594bbbb1674a13176aa47);
        

        marker_f21a8db913c7ec1d93d64ebaa54dc1b7.bindPopup(popup_a9af7f7bb2bb2b7703d4866f67cc8e4d)
        ;

        
    
    
            var marker_7d71300a5beca5df392428e10bedd0bd = L.marker(
                [55.70679, 12.536622],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_761be716f4496fc21b49881477d5806e = L.popup({"maxWidth": "100%"});

        
            var html_8512be9d341270570b530f321aa31fcb = $(`<div id="html_8512be9d341270570b530f321aa31fcb" style="width: 100.0%; height: 100.0%;">Year Built: 1935, Price:2.248.000, 49.0 m2 , ZipCode:2400 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_761be716f4496fc21b49881477d5806e.setContent(html_8512be9d341270570b530f321aa31fcb);
        

        marker_7d71300a5beca5df392428e10bedd0bd.bindPopup(popup_761be716f4496fc21b49881477d5806e)
        ;

        
    
    
            var marker_a22ec492c027798c1934d01695ace2d3 = L.marker(
                [55.725171, 12.528068],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_6d63124c1d420b03d97a4f7d831b2a9d = L.popup({"maxWidth": "100%"});

        
            var html_efbaf6a4b645fbcdab9b44bf69ed633a = $(`<div id="html_efbaf6a4b645fbcdab9b44bf69ed633a" style="width: 100.0%; height: 100.0%;">Year Built: 1930, Price:4.495.000, 133.0 m2 , ZipCode:2400 ,  Rooms:5, HomeType:Ejerlejlighed</div>`)[0];
            popup_6d63124c1d420b03d97a4f7d831b2a9d.setContent(html_efbaf6a4b645fbcdab9b44bf69ed633a);
        

        marker_a22ec492c027798c1934d01695ace2d3.bindPopup(popup_6d63124c1d420b03d97a4f7d831b2a9d)
        ;

        
    
    
            var marker_57b243b9fee6a3690a58607b922dddef = L.marker(
                [55.704239, 12.527724],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_67067f8adabf92c53a878553f5bbc737 = L.popup({"maxWidth": "100%"});

        
            var html_b83c43cb1a440fc52111d279108a066f = $(`<div id="html_b83c43cb1a440fc52111d279108a066f" style="width: 100.0%; height: 100.0%;">Year Built: 1932, Price:3.345.000, 78.0 m2 , ZipCode:2400 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_67067f8adabf92c53a878553f5bbc737.setContent(html_b83c43cb1a440fc52111d279108a066f);
        

        marker_57b243b9fee6a3690a58607b922dddef.bindPopup(popup_67067f8adabf92c53a878553f5bbc737)
        ;

        
    
    
            var marker_7a1de526c043c594cbba8177d7c59fac = L.marker(
                [55.704337, 12.527704],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_c5ea24bd1a2a3dee45608aa33dd8b8c3 = L.popup({"maxWidth": "100%"});

        
            var html_6ef40ee14d08188449418d4daa557357 = $(`<div id="html_6ef40ee14d08188449418d4daa557357" style="width: 100.0%; height: 100.0%;">Year Built: 1932, Price:2.298.000, 54.0 m2 , ZipCode:2400 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_c5ea24bd1a2a3dee45608aa33dd8b8c3.setContent(html_6ef40ee14d08188449418d4daa557357);
        

        marker_7a1de526c043c594cbba8177d7c59fac.bindPopup(popup_c5ea24bd1a2a3dee45608aa33dd8b8c3)
        ;

        
    
    
            var marker_24850be7b15fcfa2f7589652831e9ff1 = L.marker(
                [55.701929, 12.530248],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_cb225103ad355272f7c49cb814c5c817 = L.popup({"maxWidth": "100%"});

        
            var html_d2d858ae25d1ac0115c403207c332668 = $(`<div id="html_d2d858ae25d1ac0115c403207c332668" style="width: 100.0%; height: 100.0%;">Year Built: 1925, Price:2.695.000, 64.0 m2 , ZipCode:2400 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_cb225103ad355272f7c49cb814c5c817.setContent(html_d2d858ae25d1ac0115c403207c332668);
        

        marker_24850be7b15fcfa2f7589652831e9ff1.bindPopup(popup_cb225103ad355272f7c49cb814c5c817)
        ;

        
    
    
            var marker_96df679a48c1b873720d44fb2136485c = L.marker(
                [55.701258, 12.527213],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_19879a6e5f50f6cd8ebb67fee0256d46 = L.popup({"maxWidth": "100%"});

        
            var html_8ccdaa0492b4f5521c3f22008e68f6e9 = $(`<div id="html_8ccdaa0492b4f5521c3f22008e68f6e9" style="width: 100.0%; height: 100.0%;">Year Built: 1937, Price:3.495.000, 78.0 m2 , ZipCode:2400 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_19879a6e5f50f6cd8ebb67fee0256d46.setContent(html_8ccdaa0492b4f5521c3f22008e68f6e9);
        

        marker_96df679a48c1b873720d44fb2136485c.bindPopup(popup_19879a6e5f50f6cd8ebb67fee0256d46)
        ;

        
    
    
            var marker_f9a4741132891a703136fe38a8ea8ec1 = L.marker(
                [55.703558, 12.523393],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_2de9c17bc231bdb86edabebfbec31d7e = L.popup({"maxWidth": "100%"});

        
            var html_a641a97433d8b54dc72fca7567d5df75 = $(`<div id="html_a641a97433d8b54dc72fca7567d5df75" style="width: 100.0%; height: 100.0%;">Year Built: 2007, Price:4.250.000, 111.0 m2 , ZipCode:2400 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_2de9c17bc231bdb86edabebfbec31d7e.setContent(html_a641a97433d8b54dc72fca7567d5df75);
        

        marker_f9a4741132891a703136fe38a8ea8ec1.bindPopup(popup_2de9c17bc231bdb86edabebfbec31d7e)
        ;

        
    
    
            var marker_8d82f3e57a20f2309cc1a991dece1261 = L.marker(
                [55.705788, 12.527276],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_35ff0f948d26a4c416846e1b7c201d72 = L.popup({"maxWidth": "100%"});

        
            var html_69db03ec4ea14e72e54a15bd9fcac2f6 = $(`<div id="html_69db03ec4ea14e72e54a15bd9fcac2f6" style="width: 100.0%; height: 100.0%;">Year Built: 1926, Price:5.448.000, 101.0 m2 , ZipCode:2400 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_35ff0f948d26a4c416846e1b7c201d72.setContent(html_69db03ec4ea14e72e54a15bd9fcac2f6);
        

        marker_8d82f3e57a20f2309cc1a991dece1261.bindPopup(popup_35ff0f948d26a4c416846e1b7c201d72)
        ;

        
    
    
            var marker_7191010bdbe59f10ee5a9cfcfb522423 = L.marker(
                [55.701663, 12.53508],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_c5c2fb5306280fb9f9dff17ad06abab2 = L.popup({"maxWidth": "100%"});

        
            var html_be9ba4a7500725fe2432b4c5bdc41f61 = $(`<div id="html_be9ba4a7500725fe2432b4c5bdc41f61" style="width: 100.0%; height: 100.0%;">Year Built: 1936, Price:4.295.000, 98.0 m2 , ZipCode:2400 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_c5c2fb5306280fb9f9dff17ad06abab2.setContent(html_be9ba4a7500725fe2432b4c5bdc41f61);
        

        marker_7191010bdbe59f10ee5a9cfcfb522423.bindPopup(popup_c5c2fb5306280fb9f9dff17ad06abab2)
        ;

        
    
    
            var marker_27e208141722fd62db71ea0f38fb7266 = L.marker(
                [55.722858, 12.532755],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_21bfa76eab5ac7a729416e524c53dcda = L.popup({"maxWidth": "100%"});

        
            var html_7405880080cf90e96552442390fc442c = $(`<div id="html_7405880080cf90e96552442390fc442c" style="width: 100.0%; height: 100.0%;">Year Built: 1937, Price:2.145.000, 57.0 m2 , ZipCode:2400 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_21bfa76eab5ac7a729416e524c53dcda.setContent(html_7405880080cf90e96552442390fc442c);
        

        marker_27e208141722fd62db71ea0f38fb7266.bindPopup(popup_21bfa76eab5ac7a729416e524c53dcda)
        ;

        
    
    
            var marker_35f415ca493e244e9e3f87e089c40893 = L.marker(
                [55.704673, 12.52687],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_da6cb0d03f7ac197d590d859d7d777bf = L.popup({"maxWidth": "100%"});

        
            var html_f4d671718a9ea2efb1012f6e9c54b28d = $(`<div id="html_f4d671718a9ea2efb1012f6e9c54b28d" style="width: 100.0%; height: 100.0%;">Year Built: 1932, Price:2.075.000, 45.0 m2 , ZipCode:2400 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_da6cb0d03f7ac197d590d859d7d777bf.setContent(html_f4d671718a9ea2efb1012f6e9c54b28d);
        

        marker_35f415ca493e244e9e3f87e089c40893.bindPopup(popup_da6cb0d03f7ac197d590d859d7d777bf)
        ;

        
    
    
            var marker_78634f265e73c2e62f45d76cc98237a2 = L.marker(
                [55.702646, 12.531648],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_e782efa1a520f9fad7e2e55b53f48de6 = L.popup({"maxWidth": "100%"});

        
            var html_b9144d879de3ac74f3fc326e80e0188a = $(`<div id="html_b9144d879de3ac74f3fc326e80e0188a" style="width: 100.0%; height: 100.0%;">Year Built: 1970, Price:3.795.000, 119.0 m2 , ZipCode:2400 ,  Rooms:5, HomeType:Ejerlejlighed</div>`)[0];
            popup_e782efa1a520f9fad7e2e55b53f48de6.setContent(html_b9144d879de3ac74f3fc326e80e0188a);
        

        marker_78634f265e73c2e62f45d76cc98237a2.bindPopup(popup_e782efa1a520f9fad7e2e55b53f48de6)
        ;

        
    
    
            var marker_2d8b373b28234689c5a40f5534f8c878 = L.marker(
                [55.702375, 12.533726],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_278c99158d593ffaa438c37d366db3d1 = L.popup({"maxWidth": "100%"});

        
            var html_d03b4e84a99ec844401a44a804461e9a = $(`<div id="html_d03b4e84a99ec844401a44a804461e9a" style="width: 100.0%; height: 100.0%;">Year Built: 1940, Price:3.395.000, 88.0 m2 , ZipCode:2400 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_278c99158d593ffaa438c37d366db3d1.setContent(html_d03b4e84a99ec844401a44a804461e9a);
        

        marker_2d8b373b28234689c5a40f5534f8c878.bindPopup(popup_278c99158d593ffaa438c37d366db3d1)
        ;

        
    
    
            var marker_ebedfff3f24635b66981c5b1e843dd33 = L.marker(
                [55.702718, 12.588499],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_4e9852243071cbf0d2e4c22b621fedf7 = L.popup({"maxWidth": "100%"});

        
            var html_d14d79f1b817a60738418cb2f32a53da = $(`<div id="html_d14d79f1b817a60738418cb2f32a53da" style="width: 100.0%; height: 100.0%;">Year Built: 1907, Price:6.995.000, 117.0 m2 , ZipCode:2100 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_4e9852243071cbf0d2e4c22b621fedf7.setContent(html_d14d79f1b817a60738418cb2f32a53da);
        

        marker_ebedfff3f24635b66981c5b1e843dd33.bindPopup(popup_4e9852243071cbf0d2e4c22b621fedf7)
        ;

        
    
    
            var marker_6fe40ca3bb81ea3e8487f1ce1faa488b = L.marker(
                [55.711343, 12.565705],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_beac3785955c5c584b1667e63d1610b7 = L.popup({"maxWidth": "100%"});

        
            var html_23d43610961734c6e2d2a01e66e3c01a = $(`<div id="html_23d43610961734c6e2d2a01e66e3c01a" style="width: 100.0%; height: 100.0%;">Year Built: 1932, Price:3.495.000, 63.0 m2 , ZipCode:2100 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_beac3785955c5c584b1667e63d1610b7.setContent(html_23d43610961734c6e2d2a01e66e3c01a);
        

        marker_6fe40ca3bb81ea3e8487f1ce1faa488b.bindPopup(popup_beac3785955c5c584b1667e63d1610b7)
        ;

        
    
    
            var marker_10fb536a311b2dd7c82d4491730de96a = L.marker(
                [55.692263, 12.579855],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_acdd4aa85400ca4319f878abd5a4ce7d = L.popup({"maxWidth": "100%"});

        
            var html_5199fedb2ec9c437a417b2c6592e177c = $(`<div id="html_5199fedb2ec9c437a417b2c6592e177c" style="width: 100.0%; height: 100.0%;">Year Built: 2018, Price:10.200.000, 132.0 m2 , ZipCode:2100 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_acdd4aa85400ca4319f878abd5a4ce7d.setContent(html_5199fedb2ec9c437a417b2c6592e177c);
        

        marker_10fb536a311b2dd7c82d4491730de96a.bindPopup(popup_acdd4aa85400ca4319f878abd5a4ce7d)
        ;

        
    
    
            var marker_38937821868ad3c32e76978204ca8b00 = L.marker(
                [55.705039, 12.55671],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_f0664f5f5d05fe0c1ea6062b59aa924a = L.popup({"maxWidth": "100%"});

        
            var html_a809b73f75ba7bc1409e971192a9bc3c = $(`<div id="html_a809b73f75ba7bc1409e971192a9bc3c" style="width: 100.0%; height: 100.0%;">Year Built: 1926, Price:4.250.000, 72.0 m2 , ZipCode:2100 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_f0664f5f5d05fe0c1ea6062b59aa924a.setContent(html_a809b73f75ba7bc1409e971192a9bc3c);
        

        marker_38937821868ad3c32e76978204ca8b00.bindPopup(popup_f0664f5f5d05fe0c1ea6062b59aa924a)
        ;

        
    
    
            var marker_200912b9b78b5fa056eca7d3cf23fac1 = L.marker(
                [55.700727, 12.577149],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_a4f67ee5ffd889c1aea3755067fce1ce = L.popup({"maxWidth": "100%"});

        
            var html_208b78353b95d1a84500ea550cc41a90 = $(`<div id="html_208b78353b95d1a84500ea550cc41a90" style="width: 100.0%; height: 100.0%;">Year Built: 1970, Price:7.995.000, 111.0 m2 , ZipCode:2100 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_a4f67ee5ffd889c1aea3755067fce1ce.setContent(html_208b78353b95d1a84500ea550cc41a90);
        

        marker_200912b9b78b5fa056eca7d3cf23fac1.bindPopup(popup_a4f67ee5ffd889c1aea3755067fce1ce)
        ;

        
    
    
            var marker_c79577fd1f31a2823cab4470cc474f16 = L.marker(
                [55.696877, 12.593983],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_15f6cba5492debd784e1a8f313b7cf55 = L.popup({"maxWidth": "100%"});

        
            var html_1a1d1d4a1b460831e72173b1f4e5feba = $(`<div id="html_1a1d1d4a1b460831e72173b1f4e5feba" style="width: 100.0%; height: 100.0%;">Year Built: 2007, Price:7.750.000, 124.0 m2 , ZipCode:2100 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_15f6cba5492debd784e1a8f313b7cf55.setContent(html_1a1d1d4a1b460831e72173b1f4e5feba);
        

        marker_c79577fd1f31a2823cab4470cc474f16.bindPopup(popup_15f6cba5492debd784e1a8f313b7cf55)
        ;

        
    
    
            var marker_aac9f4be2266a5c1483b3f8837367eb1 = L.marker(
                [55.714495, 12.569786],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_d537537025f433db2c9f930de9b32e07 = L.popup({"maxWidth": "100%"});

        
            var html_0366b5c1ef64358a09923a5176040fc8 = $(`<div id="html_0366b5c1ef64358a09923a5176040fc8" style="width: 100.0%; height: 100.0%;">Year Built: 1906, Price:2.650.000, 58.0 m2 , ZipCode:2100 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_d537537025f433db2c9f930de9b32e07.setContent(html_0366b5c1ef64358a09923a5176040fc8);
        

        marker_aac9f4be2266a5c1483b3f8837367eb1.bindPopup(popup_d537537025f433db2c9f930de9b32e07)
        ;

        
    
    
            var marker_8c07a5643d8ec73b96e0dba5344168e3 = L.marker(
                [55.709364, 12.564737],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_178009b678dce971b7022cf5be8730fb = L.popup({"maxWidth": "100%"});

        
            var html_b008a74caefa8828055f0ab0037d9faf = $(`<div id="html_b008a74caefa8828055f0ab0037d9faf" style="width: 100.0%; height: 100.0%;">Year Built: 1934, Price:3.495.000, 66.0 m2 , ZipCode:2100 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_178009b678dce971b7022cf5be8730fb.setContent(html_b008a74caefa8828055f0ab0037d9faf);
        

        marker_8c07a5643d8ec73b96e0dba5344168e3.bindPopup(popup_178009b678dce971b7022cf5be8730fb)
        ;

        
    
    
            var marker_4860990075989b28a15ab558133a4134 = L.marker(
                [55.714495, 12.569786],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_d5a70ff18d2fa487112cb24919960f29 = L.popup({"maxWidth": "100%"});

        
            var html_9bce00cbbdd085288cd2a3074fdebe51 = $(`<div id="html_9bce00cbbdd085288cd2a3074fdebe51" style="width: 100.0%; height: 100.0%;">Year Built: 1906, Price:2.995.000, 58.0 m2 , ZipCode:2100 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_d5a70ff18d2fa487112cb24919960f29.setContent(html_9bce00cbbdd085288cd2a3074fdebe51);
        

        marker_4860990075989b28a15ab558133a4134.bindPopup(popup_d5a70ff18d2fa487112cb24919960f29)
        ;

        
    
    
            var marker_10ff24a30d06bf90e72df820103d5af4 = L.marker(
                [55.698292, 12.58013],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_b2c1d89a5dc18e5dbd1b2f94a05772d3 = L.popup({"maxWidth": "100%"});

        
            var html_98c2d96d7e354ed51c54d5594dd72c7e = $(`<div id="html_98c2d96d7e354ed51c54d5594dd72c7e" style="width: 100.0%; height: 100.0%;">Year Built: 1880, Price:8.495.000, 118.0 m2 , ZipCode:2100 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_b2c1d89a5dc18e5dbd1b2f94a05772d3.setContent(html_98c2d96d7e354ed51c54d5594dd72c7e);
        

        marker_10ff24a30d06bf90e72df820103d5af4.bindPopup(popup_b2c1d89a5dc18e5dbd1b2f94a05772d3)
        ;

        
    
    
            var marker_5aec00d33773615099163b3a936d631a = L.marker(
                [55.699291, 12.586423],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_fe6987a955900ecb8c71a2ef5604752e = L.popup({"maxWidth": "100%"});

        
            var html_eb6f498135a36238bd5a0ee0e7a73e62 = $(`<div id="html_eb6f498135a36238bd5a0ee0e7a73e62" style="width: 100.0%; height: 100.0%;">Year Built: 1896, Price:5.995.000, 82.0 m2 , ZipCode:2100 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_fe6987a955900ecb8c71a2ef5604752e.setContent(html_eb6f498135a36238bd5a0ee0e7a73e62);
        

        marker_5aec00d33773615099163b3a936d631a.bindPopup(popup_fe6987a955900ecb8c71a2ef5604752e)
        ;

        
    
    
            var marker_232b545406153f54f15c641531a39f2b = L.marker(
                [55.70104, 12.588805],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_0cccf3b1ae227ccac1694da5fee1a79c = L.popup({"maxWidth": "100%"});

        
            var html_0143664a0a9c81d839213bc085a3c5a3 = $(`<div id="html_0143664a0a9c81d839213bc085a3c5a3" style="width: 100.0%; height: 100.0%;">Year Built: 1902, Price:8.500.000, 59.0 m2 , ZipCode:2100 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_0cccf3b1ae227ccac1694da5fee1a79c.setContent(html_0143664a0a9c81d839213bc085a3c5a3);
        

        marker_232b545406153f54f15c641531a39f2b.bindPopup(popup_0cccf3b1ae227ccac1694da5fee1a79c)
        ;

        
    
    
            var marker_9ddb9ff0bf968c25957d5eb9190636f0 = L.marker(
                [55.705585, 12.579694],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_f161c238dde4c7777fc115a5ad3c45c8 = L.popup({"maxWidth": "100%"});

        
            var html_776d86272b9f3b2a44e164b238c6201c = $(`<div id="html_776d86272b9f3b2a44e164b238c6201c" style="width: 100.0%; height: 100.0%;">Year Built: 1895, Price:3.249.000, 52.0 m2 , ZipCode:2100 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_f161c238dde4c7777fc115a5ad3c45c8.setContent(html_776d86272b9f3b2a44e164b238c6201c);
        

        marker_9ddb9ff0bf968c25957d5eb9190636f0.bindPopup(popup_f161c238dde4c7777fc115a5ad3c45c8)
        ;

        
    
    
            var marker_95d2d9cff1c99a971929b6f689852951 = L.marker(
                [55.704053, 12.590571],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_ea9984ce8eb99e188db08c88442b86df = L.popup({"maxWidth": "100%"});

        
            var html_74dd164be1b02d773acc4e4547d046e3 = $(`<div id="html_74dd164be1b02d773acc4e4547d046e3" style="width: 100.0%; height: 100.0%;">Year Built: 1904, Price:4.250.000, 69.0 m2 , ZipCode:2100 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_ea9984ce8eb99e188db08c88442b86df.setContent(html_74dd164be1b02d773acc4e4547d046e3);
        

        marker_95d2d9cff1c99a971929b6f689852951.bindPopup(popup_ea9984ce8eb99e188db08c88442b86df)
        ;

        
    
    
            var marker_66853844dede1a2f144ecd4ecfb59622 = L.marker(
                [55.7076, 12.568214],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_9a51416f28600e92213a120891652a75 = L.popup({"maxWidth": "100%"});

        
            var html_2b76daecf3427f8d3edf7806c5227d0b = $(`<div id="html_2b76daecf3427f8d3edf7806c5227d0b" style="width: 100.0%; height: 100.0%;">Year Built: 1912, Price:5.695.000, 98.0 m2 , ZipCode:2100 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_9a51416f28600e92213a120891652a75.setContent(html_2b76daecf3427f8d3edf7806c5227d0b);
        

        marker_66853844dede1a2f144ecd4ecfb59622.bindPopup(popup_9a51416f28600e92213a120891652a75)
        ;

        
    
    
            var marker_ab7263ceace154e14471dcb3b7f4aec0 = L.marker(
                [55.700532, 12.580074],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_5acad3cbcac26aa6dc44b4becfebf54d = L.popup({"maxWidth": "100%"});

        
            var html_5942bee4e66796a556ef491d9a2ab750 = $(`<div id="html_5942bee4e66796a556ef491d9a2ab750" style="width: 100.0%; height: 100.0%;">Year Built: 1880, Price:8.750.000, 137.0 m2 , ZipCode:2100 ,  Rooms:5, HomeType:Ejerlejlighed</div>`)[0];
            popup_5acad3cbcac26aa6dc44b4becfebf54d.setContent(html_5942bee4e66796a556ef491d9a2ab750);
        

        marker_ab7263ceace154e14471dcb3b7f4aec0.bindPopup(popup_5acad3cbcac26aa6dc44b4becfebf54d)
        ;

        
    
    
            var marker_65b55ce45481420c411231fdcdaae8eb = L.marker(
                [55.697841, 12.582155],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_453afd4bd0b768b8e91e1abe93e7abe2 = L.popup({"maxWidth": "100%"});

        
            var html_48ccd4a76f3ca105300c1eab3023146b = $(`<div id="html_48ccd4a76f3ca105300c1eab3023146b" style="width: 100.0%; height: 100.0%;">Year Built: 1891, Price:5.475.000, 86.0 m2 , ZipCode:2100 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_453afd4bd0b768b8e91e1abe93e7abe2.setContent(html_48ccd4a76f3ca105300c1eab3023146b);
        

        marker_65b55ce45481420c411231fdcdaae8eb.bindPopup(popup_453afd4bd0b768b8e91e1abe93e7abe2)
        ;

        
    
    
            var marker_88c75cd1d6866b1d558f4481ae7963d9 = L.marker(
                [55.708989, 12.584267],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_7a03a24e62d309c33135ca668a8d7925 = L.popup({"maxWidth": "100%"});

        
            var html_75988b9f75393b6b978527e9f379ad9b = $(`<div id="html_75988b9f75393b6b978527e9f379ad9b" style="width: 100.0%; height: 100.0%;">Year Built: 1926, Price:4.195.000, 77.0 m2 , ZipCode:2100 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_7a03a24e62d309c33135ca668a8d7925.setContent(html_75988b9f75393b6b978527e9f379ad9b);
        

        marker_88c75cd1d6866b1d558f4481ae7963d9.bindPopup(popup_7a03a24e62d309c33135ca668a8d7925)
        ;

        
    
    
            var marker_4e33d71dfdd2605a02041d664480e644 = L.marker(
                [55.707441, 12.571763],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_7c06596a5492d5373a7a6aded62d21eb = L.popup({"maxWidth": "100%"});

        
            var html_02e07da130c86b1a295eb5652e4d900d = $(`<div id="html_02e07da130c86b1a295eb5652e4d900d" style="width: 100.0%; height: 100.0%;">Year Built: 1920, Price:10.695.000, 182.0 m2 , ZipCode:2100 ,  Rooms:5, HomeType:Ejerlejlighed</div>`)[0];
            popup_7c06596a5492d5373a7a6aded62d21eb.setContent(html_02e07da130c86b1a295eb5652e4d900d);
        

        marker_4e33d71dfdd2605a02041d664480e644.bindPopup(popup_7c06596a5492d5373a7a6aded62d21eb)
        ;

        
    
    
            var marker_6ad0899c6e3a803249b9ae73ed93c66a = L.marker(
                [55.71312, 12.57137],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_fdef424a1a42a747353b1ff35a3932eb = L.popup({"maxWidth": "100%"});

        
            var html_d83806db6750956ac6c2cb17c75efdf4 = $(`<div id="html_d83806db6750956ac6c2cb17c75efdf4" style="width: 100.0%; height: 100.0%;">Year Built: 1902, Price:2.795.000, 54.0 m2 , ZipCode:2100 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_fdef424a1a42a747353b1ff35a3932eb.setContent(html_d83806db6750956ac6c2cb17c75efdf4);
        

        marker_6ad0899c6e3a803249b9ae73ed93c66a.bindPopup(popup_fdef424a1a42a747353b1ff35a3932eb)
        ;

        
    
    
            var marker_a560f4547cfa63f85f5eb1377b688615 = L.marker(
                [55.698578, 12.59148],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_826dbee1939051553c591afc3f701bac = L.popup({"maxWidth": "100%"});

        
            var html_848de5cfb175732fe63d33b37db85b8e = $(`<div id="html_848de5cfb175732fe63d33b37db85b8e" style="width: 100.0%; height: 100.0%;">Year Built: 1931, Price:7.495.000, 123.0 m2 , ZipCode:2100 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_826dbee1939051553c591afc3f701bac.setContent(html_848de5cfb175732fe63d33b37db85b8e);
        

        marker_a560f4547cfa63f85f5eb1377b688615.bindPopup(popup_826dbee1939051553c591afc3f701bac)
        ;

        
    
    
            var marker_14bd5ad59193484c4cd05cf636c620bb = L.marker(
                [55.701246, 12.577723],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_a7f29e85f8d0c1d8c48ea04a92df07eb = L.popup({"maxWidth": "100%"});

        
            var html_2f2af5a4d0e1e6b713513aab56c2dfbf = $(`<div id="html_2f2af5a4d0e1e6b713513aab56c2dfbf" style="width: 100.0%; height: 100.0%;">Year Built: 1904, Price:10.995.000, 151.0 m2 , ZipCode:2100 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_a7f29e85f8d0c1d8c48ea04a92df07eb.setContent(html_2f2af5a4d0e1e6b713513aab56c2dfbf);
        

        marker_14bd5ad59193484c4cd05cf636c620bb.bindPopup(popup_a7f29e85f8d0c1d8c48ea04a92df07eb)
        ;

        
    
    
            var marker_68889c37a7f6f31629551e1adf709cad = L.marker(
                [55.706157, 12.577703],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_b89e5fef690c80855b822a49777001b2 = L.popup({"maxWidth": "100%"});

        
            var html_a69bcd888a024961f365b5bbbf572983 = $(`<div id="html_a69bcd888a024961f365b5bbbf572983" style="width: 100.0%; height: 100.0%;">Year Built: 1889, Price:21.000.000, 284.0 m2 , ZipCode:2100 ,  Rooms:7, HomeType:Ejerlejlighed</div>`)[0];
            popup_b89e5fef690c80855b822a49777001b2.setContent(html_a69bcd888a024961f365b5bbbf572983);
        

        marker_68889c37a7f6f31629551e1adf709cad.bindPopup(popup_b89e5fef690c80855b822a49777001b2)
        ;

        
    
    
            var marker_dd2d75413c21277c212d2dabd99a3df8 = L.marker(
                [55.704016, 12.578857],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_d050f4e3ac8738ad073e935c76caaf0b = L.popup({"maxWidth": "100%"});

        
            var html_b7a86abaee2d4b81b9a829e66f144834 = $(`<div id="html_b7a86abaee2d4b81b9a829e66f144834" style="width: 100.0%; height: 100.0%;">Year Built: 1907, Price:7.795.000, 111.0 m2 , ZipCode:2100 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_d050f4e3ac8738ad073e935c76caaf0b.setContent(html_b7a86abaee2d4b81b9a829e66f144834);
        

        marker_dd2d75413c21277c212d2dabd99a3df8.bindPopup(popup_d050f4e3ac8738ad073e935c76caaf0b)
        ;

        
    
    
            var marker_36b8df942d7e4b8b787e5cf78a2a5236 = L.marker(
                [55.709446, 12.565308],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_4386d3cdfda1a55ffb4767bd4295948a = L.popup({"maxWidth": "100%"});

        
            var html_42e8f2bea90937111d4927ababb7cec2 = $(`<div id="html_42e8f2bea90937111d4927ababb7cec2" style="width: 100.0%; height: 100.0%;">Year Built: 1934, Price:2.745.000, 57.0 m2 , ZipCode:2100 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_4386d3cdfda1a55ffb4767bd4295948a.setContent(html_42e8f2bea90937111d4927ababb7cec2);
        

        marker_36b8df942d7e4b8b787e5cf78a2a5236.bindPopup(popup_4386d3cdfda1a55ffb4767bd4295948a)
        ;

        
    
    
            var marker_9ceedcadae65a0161a525cbdbab2b132 = L.marker(
                [55.707327, 12.584606],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_be6f39b9629519836ffd4437abee56d9 = L.popup({"maxWidth": "100%"});

        
            var html_2e32be8b0164ab93f4b337f396de7ce0 = $(`<div id="html_2e32be8b0164ab93f4b337f396de7ce0" style="width: 100.0%; height: 100.0%;">Year Built: 1913, Price:4.798.000, 80.0 m2 , ZipCode:2100 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_be6f39b9629519836ffd4437abee56d9.setContent(html_2e32be8b0164ab93f4b337f396de7ce0);
        

        marker_9ceedcadae65a0161a525cbdbab2b132.bindPopup(popup_be6f39b9629519836ffd4437abee56d9)
        ;

        
    
    
            var marker_e775dcb1f39b7a579420269c8f0fac36 = L.marker(
                [55.697494, 12.597758],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_fc058a4ce0e063ef88d548bf7878cb0b = L.popup({"maxWidth": "100%"});

        
            var html_fa431876bf98d3e74211bdae1e771049 = $(`<div id="html_fa431876bf98d3e74211bdae1e771049" style="width: 100.0%; height: 100.0%;">Year Built: 1994, Price:6.895.000, 97.0 m2 , ZipCode:2100 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_fc058a4ce0e063ef88d548bf7878cb0b.setContent(html_fa431876bf98d3e74211bdae1e771049);
        

        marker_e775dcb1f39b7a579420269c8f0fac36.bindPopup(popup_fc058a4ce0e063ef88d548bf7878cb0b)
        ;

        
    
    
            var marker_c1e3351482b182425d17d286e4fbcbd4 = L.marker(
                [55.695061, 12.589585],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_fa7e9df2649b692a316657f88cebbf48 = L.popup({"maxWidth": "100%"});

        
            var html_957d0da3d134bbf8689f8bc5ac3d92a1 = $(`<div id="html_957d0da3d134bbf8689f8bc5ac3d92a1" style="width: 100.0%; height: 100.0%;">Year Built: 1932, Price:12.500.000, 140.0 m2 , ZipCode:2100 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_fa7e9df2649b692a316657f88cebbf48.setContent(html_957d0da3d134bbf8689f8bc5ac3d92a1);
        

        marker_c1e3351482b182425d17d286e4fbcbd4.bindPopup(popup_fa7e9df2649b692a316657f88cebbf48)
        ;

        
    
    
            var marker_3a8d75b51c835b4eefc00737df936f1b = L.marker(
                [55.698581, 12.580458],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_327a512280818a785a089ab0f4bb7882 = L.popup({"maxWidth": "100%"});

        
            var html_e1494698ddbd5d32467288c244366b6d = $(`<div id="html_e1494698ddbd5d32467288c244366b6d" style="width: 100.0%; height: 100.0%;">Year Built: 1894, Price:6.000.000, 117.0 m2 , ZipCode:2100 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_327a512280818a785a089ab0f4bb7882.setContent(html_e1494698ddbd5d32467288c244366b6d);
        

        marker_3a8d75b51c835b4eefc00737df936f1b.bindPopup(popup_327a512280818a785a089ab0f4bb7882)
        ;

        
    
    
            var marker_8bffd4cbbac3be219763cabafa48d083 = L.marker(
                [55.700722, 12.580186],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_4a99a1472a237430f11fd20938b41846 = L.popup({"maxWidth": "100%"});

        
            var html_901d51b442443886895cfb45b9385cb9 = $(`<div id="html_901d51b442443886895cfb45b9385cb9" style="width: 100.0%; height: 100.0%;">Year Built: 1881, Price:5.995.000, 90.0 m2 , ZipCode:2100 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_4a99a1472a237430f11fd20938b41846.setContent(html_901d51b442443886895cfb45b9385cb9);
        

        marker_8bffd4cbbac3be219763cabafa48d083.bindPopup(popup_4a99a1472a237430f11fd20938b41846)
        ;

        
    
    
            var marker_14ec2a7aad18a85e3b045dba2eaad459 = L.marker(
                [55.7089, 12.583394],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_cb51a88c157601cc04ebdfae3a415b12 = L.popup({"maxWidth": "100%"});

        
            var html_528cde69c1b756a4c6c2a871859024f7 = $(`<div id="html_528cde69c1b756a4c6c2a871859024f7" style="width: 100.0%; height: 100.0%;">Year Built: 1909, Price:3.095.000, 58.0 m2 , ZipCode:2100 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_cb51a88c157601cc04ebdfae3a415b12.setContent(html_528cde69c1b756a4c6c2a871859024f7);
        

        marker_14ec2a7aad18a85e3b045dba2eaad459.bindPopup(popup_cb51a88c157601cc04ebdfae3a415b12)
        ;

        
    
    
            var marker_792f41959f62b590e1fa1c2f486ffb3d = L.marker(
                [55.709636, 12.578993],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_f90dbe5c2ccd14d4a37f2abf0aebf25a = L.popup({"maxWidth": "100%"});

        
            var html_18040c54a6b5e1ba621875137d8e8d7f = $(`<div id="html_18040c54a6b5e1ba621875137d8e8d7f" style="width: 100.0%; height: 100.0%;">Year Built: 1903, Price:3.395.000, 57.0 m2 , ZipCode:2100 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_f90dbe5c2ccd14d4a37f2abf0aebf25a.setContent(html_18040c54a6b5e1ba621875137d8e8d7f);
        

        marker_792f41959f62b590e1fa1c2f486ffb3d.bindPopup(popup_f90dbe5c2ccd14d4a37f2abf0aebf25a)
        ;

        
    
    
            var marker_e3557c46013b3a6a94292e006275927e = L.marker(
                [55.696884, 12.593679],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_6d784198bba44f4213de2726ae4e4a14 = L.popup({"maxWidth": "100%"});

        
            var html_ba6a7f5beb086558110bf8614b6d4bba = $(`<div id="html_ba6a7f5beb086558110bf8614b6d4bba" style="width: 100.0%; height: 100.0%;">Year Built: 2007, Price:6.995.000, 112.0 m2 , ZipCode:2100 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_6d784198bba44f4213de2726ae4e4a14.setContent(html_ba6a7f5beb086558110bf8614b6d4bba);
        

        marker_e3557c46013b3a6a94292e006275927e.bindPopup(popup_6d784198bba44f4213de2726ae4e4a14)
        ;

        
    
    
            var marker_b8e36b98ab15638444c0b5ef143f3fb2 = L.marker(
                [55.708704, 12.58479],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_c677c1aad28637941b551dd4d4135a63 = L.popup({"maxWidth": "100%"});

        
            var html_59d16cf08eb1947edc8747f7528c49de = $(`<div id="html_59d16cf08eb1947edc8747f7528c49de" style="width: 100.0%; height: 100.0%;">Year Built: 1915, Price:12.495.000, 193.0 m2 , ZipCode:2100 ,  Rooms:7, HomeType:Ejerlejlighed</div>`)[0];
            popup_c677c1aad28637941b551dd4d4135a63.setContent(html_59d16cf08eb1947edc8747f7528c49de);
        

        marker_b8e36b98ab15638444c0b5ef143f3fb2.bindPopup(popup_c677c1aad28637941b551dd4d4135a63)
        ;

        
    
    
            var marker_c5943efbffff0baedf41bd7b0dd7e481 = L.marker(
                [55.702312, 12.580491],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_523285321ab202a7af7e96eb3f86498e = L.popup({"maxWidth": "100%"});

        
            var html_c678b74df8f14aebb576ee1ed17e6826 = $(`<div id="html_c678b74df8f14aebb576ee1ed17e6826" style="width: 100.0%; height: 100.0%;">Year Built: 1903, Price:13.995.000, 224.0 m2 , ZipCode:2100 ,  Rooms:6, HomeType:Ejerlejlighed</div>`)[0];
            popup_523285321ab202a7af7e96eb3f86498e.setContent(html_c678b74df8f14aebb576ee1ed17e6826);
        

        marker_c5943efbffff0baedf41bd7b0dd7e481.bindPopup(popup_523285321ab202a7af7e96eb3f86498e)
        ;

        
    
    
            var marker_87467bafa7207cbc3e0f8921c8dabdd4 = L.marker(
                [55.700301, 12.586813],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_ae4b79a6349ef936755a9020e104f05f = L.popup({"maxWidth": "100%"});

        
            var html_71408b036177619de523a631795c37c7 = $(`<div id="html_71408b036177619de523a631795c37c7" style="width: 100.0%; height: 100.0%;">Year Built: 1900, Price:5.795.000, 87.0 m2 , ZipCode:2100 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_ae4b79a6349ef936755a9020e104f05f.setContent(html_71408b036177619de523a631795c37c7);
        

        marker_87467bafa7207cbc3e0f8921c8dabdd4.bindPopup(popup_ae4b79a6349ef936755a9020e104f05f)
        ;

        
    
    
            var marker_987b8d4c32c8a872755e236166ec2824 = L.marker(
                [55.708347, 12.582069],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_5842e558c674205936027b89700b2070 = L.popup({"maxWidth": "100%"});

        
            var html_7c0eb82bbfa32917302559fa85fcfb34 = $(`<div id="html_7c0eb82bbfa32917302559fa85fcfb34" style="width: 100.0%; height: 100.0%;">Year Built: 1914, Price:2.995.000, 73.0 m2 , ZipCode:2100 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_5842e558c674205936027b89700b2070.setContent(html_7c0eb82bbfa32917302559fa85fcfb34);
        

        marker_987b8d4c32c8a872755e236166ec2824.bindPopup(popup_5842e558c674205936027b89700b2070)
        ;

        
    
    
            var marker_146b2b07085775f3d04916456f5d7e32 = L.marker(
                [55.705827, 12.555136],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_0a9177d9ea9692d3ef0071965e52f690 = L.popup({"maxWidth": "100%"});

        
            var html_1cfa918aa9520092c465d6f879a19e28 = $(`<div id="html_1cfa918aa9520092c465d6f879a19e28" style="width: 100.0%; height: 100.0%;">Year Built: 1926, Price:3.795.000, 72.0 m2 , ZipCode:2100 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_0a9177d9ea9692d3ef0071965e52f690.setContent(html_1cfa918aa9520092c465d6f879a19e28);
        

        marker_146b2b07085775f3d04916456f5d7e32.bindPopup(popup_0a9177d9ea9692d3ef0071965e52f690)
        ;

        
    
    
            var marker_8c269dfd4fc7392880c8327ecf39010d = L.marker(
                [55.699993, 12.592938],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_6bf03771f29fba4aa5f60bacc4f74265 = L.popup({"maxWidth": "100%"});

        
            var html_715f13a33ebb03221fd1eb96352d2d05 = $(`<div id="html_715f13a33ebb03221fd1eb96352d2d05" style="width: 100.0%; height: 100.0%;">Year Built: 2017, Price:5.498.000, 94.0 m2 , ZipCode:2100 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_6bf03771f29fba4aa5f60bacc4f74265.setContent(html_715f13a33ebb03221fd1eb96352d2d05);
        

        marker_8c269dfd4fc7392880c8327ecf39010d.bindPopup(popup_6bf03771f29fba4aa5f60bacc4f74265)
        ;

        
    
    
            var marker_6e477d653a417f505177c1bee3d667a7 = L.marker(
                [55.697738, 12.583855],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_6a01f621f0e868c6bad6a68a5eaedc50 = L.popup({"maxWidth": "100%"});

        
            var html_ed5d31df22461a11312d1f0b27d5110c = $(`<div id="html_ed5d31df22461a11312d1f0b27d5110c" style="width: 100.0%; height: 100.0%;">Year Built: 1908, Price:7.995.000, 120.0 m2 , ZipCode:2100 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_6a01f621f0e868c6bad6a68a5eaedc50.setContent(html_ed5d31df22461a11312d1f0b27d5110c);
        

        marker_6e477d653a417f505177c1bee3d667a7.bindPopup(popup_6a01f621f0e868c6bad6a68a5eaedc50)
        ;

        
    
    
            var marker_9380dcaa8fecf2c93c07e6a237ec878f = L.marker(
                [55.70402, 12.590221],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_7dac3f17c9b6e6f30f218209706990ca = L.popup({"maxWidth": "100%"});

        
            var html_f5607b01d0d23338df0111c1d3c07e2d = $(`<div id="html_f5607b01d0d23338df0111c1d3c07e2d" style="width: 100.0%; height: 100.0%;">Year Built: 1904, Price:4.795.000, 71.0 m2 , ZipCode:2100 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_7dac3f17c9b6e6f30f218209706990ca.setContent(html_f5607b01d0d23338df0111c1d3c07e2d);
        

        marker_9380dcaa8fecf2c93c07e6a237ec878f.bindPopup(popup_7dac3f17c9b6e6f30f218209706990ca)
        ;

        
    
    
            var marker_9d4ae6e1918e08d0fdae846b0ae50a1c = L.marker(
                [55.708993, 12.583471],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_f4cb6098f2edba786956f4984c191b49 = L.popup({"maxWidth": "100%"});

        
            var html_185c88af2a7cfed9bf2ca26aae397eef = $(`<div id="html_185c88af2a7cfed9bf2ca26aae397eef" style="width: 100.0%; height: 100.0%;">Year Built: 1909, Price:6.495.000, 98.0 m2 , ZipCode:2100 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_f4cb6098f2edba786956f4984c191b49.setContent(html_185c88af2a7cfed9bf2ca26aae397eef);
        

        marker_9d4ae6e1918e08d0fdae846b0ae50a1c.bindPopup(popup_f4cb6098f2edba786956f4984c191b49)
        ;

        
    
    
            var marker_b4b7b82d1c771aec0ec1d2b9f48f5971 = L.marker(
                [55.708663, 12.56434],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_77f48039aa4cdbe9298276a1019f142f = L.popup({"maxWidth": "100%"});

        
            var html_3adf1e1b1aa5798ba96a3955a40ad507 = $(`<div id="html_3adf1e1b1aa5798ba96a3955a40ad507" style="width: 100.0%; height: 100.0%;">Year Built: 1930, Price:3.795.000, 68.0 m2 , ZipCode:2100 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_77f48039aa4cdbe9298276a1019f142f.setContent(html_3adf1e1b1aa5798ba96a3955a40ad507);
        

        marker_b4b7b82d1c771aec0ec1d2b9f48f5971.bindPopup(popup_77f48039aa4cdbe9298276a1019f142f)
        ;

        
    
    
            var marker_a33fd6562aa861dcf065e7b64beb9d15 = L.marker(
                [55.698542, 12.593873],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_4fb10c17c55911b239c485de6d7f0426 = L.popup({"maxWidth": "100%"});

        
            var html_0e9955f29ca2a383f898ea4c46576e63 = $(`<div id="html_0e9955f29ca2a383f898ea4c46576e63" style="width: 100.0%; height: 100.0%;">Year Built: 2007, Price:9.500.000, 130.0 m2 , ZipCode:2100 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_4fb10c17c55911b239c485de6d7f0426.setContent(html_0e9955f29ca2a383f898ea4c46576e63);
        

        marker_a33fd6562aa861dcf065e7b64beb9d15.bindPopup(popup_4fb10c17c55911b239c485de6d7f0426)
        ;

        
    
    
            var marker_e7c6ead1348688d44fc21f2a5521b8d7 = L.marker(
                [55.703301, 12.5883],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_c4dc3ec7365f8743165907e7b22fa74a = L.popup({"maxWidth": "100%"});

        
            var html_468eee9019442946da88e521edf21210 = $(`<div id="html_468eee9019442946da88e521edf21210" style="width: 100.0%; height: 100.0%;">Year Built: 1901, Price:12.995.000, 169.0 m2 , ZipCode:2100 ,  Rooms:6, HomeType:Ejerlejlighed</div>`)[0];
            popup_c4dc3ec7365f8743165907e7b22fa74a.setContent(html_468eee9019442946da88e521edf21210);
        

        marker_e7c6ead1348688d44fc21f2a5521b8d7.bindPopup(popup_c4dc3ec7365f8743165907e7b22fa74a)
        ;

        
    
    
            var marker_ddc4bc4e42636210b5e5820b732ec5c0 = L.marker(
                [55.712028, 12.574019],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_3267832175c137e74673cdb0c5c5b8c6 = L.popup({"maxWidth": "100%"});

        
            var html_a2126d32e90c042e22fdfc60d38f9799 = $(`<div id="html_a2126d32e90c042e22fdfc60d38f9799" style="width: 100.0%; height: 100.0%;">Year Built: 1899, Price:2.995.000, 49.0 m2 , ZipCode:2100 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_3267832175c137e74673cdb0c5c5b8c6.setContent(html_a2126d32e90c042e22fdfc60d38f9799);
        

        marker_ddc4bc4e42636210b5e5820b732ec5c0.bindPopup(popup_3267832175c137e74673cdb0c5c5b8c6)
        ;

        
    
    
            var marker_2895daad0d1ce8f6a87c99edc7f87465 = L.marker(
                [55.706682, 12.57864],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_a262c9457b53eab7fb48499038b95c4c = L.popup({"maxWidth": "100%"});

        
            var html_80aacf8d1d16101731e37323a7d71dd2 = $(`<div id="html_80aacf8d1d16101731e37323a7d71dd2" style="width: 100.0%; height: 100.0%;">Year Built: 1905, Price:5.750.000, 91.0 m2 , ZipCode:2100 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_a262c9457b53eab7fb48499038b95c4c.setContent(html_80aacf8d1d16101731e37323a7d71dd2);
        

        marker_2895daad0d1ce8f6a87c99edc7f87465.bindPopup(popup_a262c9457b53eab7fb48499038b95c4c)
        ;

        
    
    
            var marker_86af0a0a0856430a0b6a49e457cdad77 = L.marker(
                [55.707688, 12.570956],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_6c84e89cfb7e80e3f48b380a4d598c88 = L.popup({"maxWidth": "100%"});

        
            var html_a8a96117d04dcc35141fcf64ee38eaaa = $(`<div id="html_a8a96117d04dcc35141fcf64ee38eaaa" style="width: 100.0%; height: 100.0%;">Year Built: 1920, Price:5.995.000, 120.0 m2 , ZipCode:2100 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_6c84e89cfb7e80e3f48b380a4d598c88.setContent(html_a8a96117d04dcc35141fcf64ee38eaaa);
        

        marker_86af0a0a0856430a0b6a49e457cdad77.bindPopup(popup_6c84e89cfb7e80e3f48b380a4d598c88)
        ;

        
    
    
            var marker_36776b116d9075bf424d1188aec1ea42 = L.marker(
                [55.697815, 12.585894],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_c9159dbb4c28d69f40a657f266f33567 = L.popup({"maxWidth": "100%"});

        
            var html_2d99ce4735a0be1e566961d3ffc6c1da = $(`<div id="html_2d99ce4735a0be1e566961d3ffc6c1da" style="width: 100.0%; height: 100.0%;">Year Built: 1895, Price:6.995.000, 97.0 m2 , ZipCode:2100 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_c9159dbb4c28d69f40a657f266f33567.setContent(html_2d99ce4735a0be1e566961d3ffc6c1da);
        

        marker_36776b116d9075bf424d1188aec1ea42.bindPopup(popup_c9159dbb4c28d69f40a657f266f33567)
        ;

        
    
    
            var marker_1168219ee5a56e2f34503f4d24a45265 = L.marker(
                [55.705752, 12.579959],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_fd2947f180a4bd1d9beab64932450c82 = L.popup({"maxWidth": "100%"});

        
            var html_aef609b1a0c6f130f7486e5d4ff938f8 = $(`<div id="html_aef609b1a0c6f130f7486e5d4ff938f8" style="width: 100.0%; height: 100.0%;">Year Built: 1892, Price:3.450.000, 53.0 m2 , ZipCode:2100 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_fd2947f180a4bd1d9beab64932450c82.setContent(html_aef609b1a0c6f130f7486e5d4ff938f8);
        

        marker_1168219ee5a56e2f34503f4d24a45265.bindPopup(popup_fd2947f180a4bd1d9beab64932450c82)
        ;

        
    
    
            var marker_74292c20f4049b36c9d30b165a5b4e8f = L.marker(
                [55.707501, 12.588325],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_4a4d96a0f3b103986c4425522624e550 = L.popup({"maxWidth": "100%"});

        
            var html_e9fd594cb15014adebc9b74ef4c2a372 = $(`<div id="html_e9fd594cb15014adebc9b74ef4c2a372" style="width: 100.0%; height: 100.0%;">Year Built: 1935, Price:3.695.000, 64.0 m2 , ZipCode:2100 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_4a4d96a0f3b103986c4425522624e550.setContent(html_e9fd594cb15014adebc9b74ef4c2a372);
        

        marker_74292c20f4049b36c9d30b165a5b4e8f.bindPopup(popup_4a4d96a0f3b103986c4425522624e550)
        ;

        
    
    
            var marker_5f583d7b24b16609275e3b7e9a868855 = L.marker(
                [55.712099, 12.560252],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_edbad11e3b26663c2cda4ee432ef8c41 = L.popup({"maxWidth": "100%"});

        
            var html_dca93ce11c93d5881d89be3f48bb8a70 = $(`<div id="html_dca93ce11c93d5881d89be3f48bb8a70" style="width: 100.0%; height: 100.0%;">Year Built: 1927, Price:5.495.000, 123.0 m2 , ZipCode:2100 ,  Rooms:5, HomeType:Ejerlejlighed</div>`)[0];
            popup_edbad11e3b26663c2cda4ee432ef8c41.setContent(html_dca93ce11c93d5881d89be3f48bb8a70);
        

        marker_5f583d7b24b16609275e3b7e9a868855.bindPopup(popup_edbad11e3b26663c2cda4ee432ef8c41)
        ;

        
    
    
            var marker_93fcaa1b44ac14320ec16fd1b632c183 = L.marker(
                [55.710768, 12.566057],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_0ec4800cb8afdf852cc4eefb1a74b074 = L.popup({"maxWidth": "100%"});

        
            var html_8119b0b343301d9506f129f2b12fc75c = $(`<div id="html_8119b0b343301d9506f129f2b12fc75c" style="width: 100.0%; height: 100.0%;">Year Built: 1932, Price:4.195.000, 72.0 m2 , ZipCode:2100 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_0ec4800cb8afdf852cc4eefb1a74b074.setContent(html_8119b0b343301d9506f129f2b12fc75c);
        

        marker_93fcaa1b44ac14320ec16fd1b632c183.bindPopup(popup_0ec4800cb8afdf852cc4eefb1a74b074)
        ;

        
    
    
            var marker_ad171ded787558ec757ce1809216fc63 = L.marker(
                [55.719136, 12.577434],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_cade816cd69fc7d2cf04d5302fc4bc1b = L.popup({"maxWidth": "100%"});

        
            var html_c54417a5b63dba1d9a9ff4fc81ba79ea = $(`<div id="html_c54417a5b63dba1d9a9ff4fc81ba79ea" style="width: 100.0%; height: 100.0%;">Year Built: 1931, Price:4.195.000, 76.0 m2 , ZipCode:2100 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_cade816cd69fc7d2cf04d5302fc4bc1b.setContent(html_c54417a5b63dba1d9a9ff4fc81ba79ea);
        

        marker_ad171ded787558ec757ce1809216fc63.bindPopup(popup_cade816cd69fc7d2cf04d5302fc4bc1b)
        ;

        
    
    
            var marker_08826046c0e29b4acc029600e085a834 = L.marker(
                [55.707103, 12.583675],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_f73004544d8c43e7d6465fbf783e7639 = L.popup({"maxWidth": "100%"});

        
            var html_6bed74b92ee9c72b17aef76930d5bb66 = $(`<div id="html_6bed74b92ee9c72b17aef76930d5bb66" style="width: 100.0%; height: 100.0%;">Year Built: 1911, Price:4.295.000, 65.0 m2 , ZipCode:2100 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_f73004544d8c43e7d6465fbf783e7639.setContent(html_6bed74b92ee9c72b17aef76930d5bb66);
        

        marker_08826046c0e29b4acc029600e085a834.bindPopup(popup_f73004544d8c43e7d6465fbf783e7639)
        ;

        
    
    
            var marker_a977dbaf4f4392a98ad033f3bdb9d5d1 = L.marker(
                [55.7076, 12.568214],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_09c7e5f393a91eb88096a2f66fa41a98 = L.popup({"maxWidth": "100%"});

        
            var html_ddcf6577ebe82377184c029c46e2d46b = $(`<div id="html_ddcf6577ebe82377184c029c46e2d46b" style="width: 100.0%; height: 100.0%;">Year Built: 1912, Price:4.745.000, 85.0 m2 , ZipCode:2100 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_09c7e5f393a91eb88096a2f66fa41a98.setContent(html_ddcf6577ebe82377184c029c46e2d46b);
        

        marker_a977dbaf4f4392a98ad033f3bdb9d5d1.bindPopup(popup_09c7e5f393a91eb88096a2f66fa41a98)
        ;

        
    
    
            var marker_1e9cb6ee48de5cc5cadd5d321d6a084f = L.marker(
                [55.707761, 12.569077],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_9507b888b5d997b739e9e61f0af8fc14 = L.popup({"maxWidth": "100%"});

        
            var html_2c7d32e0895cea36346f2f4735c7b446 = $(`<div id="html_2c7d32e0895cea36346f2f4735c7b446" style="width: 100.0%; height: 100.0%;">Year Built: 1912, Price:6.795.000, 126.0 m2 , ZipCode:2100 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_9507b888b5d997b739e9e61f0af8fc14.setContent(html_2c7d32e0895cea36346f2f4735c7b446);
        

        marker_1e9cb6ee48de5cc5cadd5d321d6a084f.bindPopup(popup_9507b888b5d997b739e9e61f0af8fc14)
        ;

        
    
    
            var marker_5bf53de1c9ac69629cdfe34c03fb97d3 = L.marker(
                [55.703679, 12.586863],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_bde5962a27079472cc6465f9f37fd004 = L.popup({"maxWidth": "100%"});

        
            var html_bd24039f3c4decc92afda31ef88dce3b = $(`<div id="html_bd24039f3c4decc92afda31ef88dce3b" style="width: 100.0%; height: 100.0%;">Year Built: 1902, Price:3.095.000, 55.0 m2 , ZipCode:2100 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_bde5962a27079472cc6465f9f37fd004.setContent(html_bd24039f3c4decc92afda31ef88dce3b);
        

        marker_5bf53de1c9ac69629cdfe34c03fb97d3.bindPopup(popup_bde5962a27079472cc6465f9f37fd004)
        ;

        
    
    
            var marker_64b1b04337999addd516ae8aceaac054 = L.marker(
                [55.697484, 12.587268],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_bb48e81ec0a232ab6995e6f7fbf1522b = L.popup({"maxWidth": "100%"});

        
            var html_40ba0c8ba06f54a842ebaeb34118aa6c = $(`<div id="html_40ba0c8ba06f54a842ebaeb34118aa6c" style="width: 100.0%; height: 100.0%;">Year Built: 1907, Price:17.500.000, 226.0 m2 , ZipCode:2100 ,  Rooms:6, HomeType:Ejerlejlighed</div>`)[0];
            popup_bb48e81ec0a232ab6995e6f7fbf1522b.setContent(html_40ba0c8ba06f54a842ebaeb34118aa6c);
        

        marker_64b1b04337999addd516ae8aceaac054.bindPopup(popup_bb48e81ec0a232ab6995e6f7fbf1522b)
        ;

        
    
    
            var marker_5d860f84efa03de989ee7a299218dab8 = L.marker(
                [55.699865, 12.587703],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_27efc28a65e98abdf45a7bcd73e4c3f7 = L.popup({"maxWidth": "100%"});

        
            var html_f2a1add221441c66bca62d8093ce9333 = $(`<div id="html_f2a1add221441c66bca62d8093ce9333" style="width: 100.0%; height: 100.0%;">Year Built: 1900, Price:3.795.000, 54.0 m2 , ZipCode:2100 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_27efc28a65e98abdf45a7bcd73e4c3f7.setContent(html_f2a1add221441c66bca62d8093ce9333);
        

        marker_5d860f84efa03de989ee7a299218dab8.bindPopup(popup_27efc28a65e98abdf45a7bcd73e4c3f7)
        ;

        
    
    
            var marker_71c8c609d2c07bc13a6b156a88dd9c9a = L.marker(
                [55.707778, 12.584293],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_2a78d6d94d61906c9139b58f1cc45fdc = L.popup({"maxWidth": "100%"});

        
            var html_4703e8bd4e727c4dd6833143df49ab4c = $(`<div id="html_4703e8bd4e727c4dd6833143df49ab4c" style="width: 100.0%; height: 100.0%;">Year Built: 1916, Price:4.950.000, 83.0 m2 , ZipCode:2100 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_2a78d6d94d61906c9139b58f1cc45fdc.setContent(html_4703e8bd4e727c4dd6833143df49ab4c);
        

        marker_71c8c609d2c07bc13a6b156a88dd9c9a.bindPopup(popup_2a78d6d94d61906c9139b58f1cc45fdc)
        ;

        
    
    
            var marker_808cc63784fb6fc0e4aafb551ea8c8a9 = L.marker(
                [55.697233, 12.582479],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_c8ff3676091570bfb9f17ded62396b42 = L.popup({"maxWidth": "100%"});

        
            var html_fbee62ee14612585bc2ac46e88cfb1d7 = $(`<div id="html_fbee62ee14612585bc2ac46e88cfb1d7" style="width: 100.0%; height: 100.0%;">Year Built: 1909, Price:8.850.000, 136.0 m2 , ZipCode:2100 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_c8ff3676091570bfb9f17ded62396b42.setContent(html_fbee62ee14612585bc2ac46e88cfb1d7);
        

        marker_808cc63784fb6fc0e4aafb551ea8c8a9.bindPopup(popup_c8ff3676091570bfb9f17ded62396b42)
        ;

        
    
    
            var marker_441c1410fcf8f6caae5d361b8cd34bba = L.marker(
                [55.709437, 12.562338],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_d901ef099d6cdd9912143ac5226cac29 = L.popup({"maxWidth": "100%"});

        
            var html_931a511cf1a069190a74c994e219fb99 = $(`<div id="html_931a511cf1a069190a74c994e219fb99" style="width: 100.0%; height: 100.0%;">Year Built: 1972, Price:2.595.000, 64.0 m2 , ZipCode:2100 ,  Rooms:1, HomeType:Ejerlejlighed</div>`)[0];
            popup_d901ef099d6cdd9912143ac5226cac29.setContent(html_931a511cf1a069190a74c994e219fb99);
        

        marker_441c1410fcf8f6caae5d361b8cd34bba.bindPopup(popup_d901ef099d6cdd9912143ac5226cac29)
        ;

        
    
    
            var marker_f30793bbd5c10bcc4984381a7bd266a7 = L.marker(
                [55.699325, 12.595431],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_78e21367fc11335e95f6e660373302f8 = L.popup({"maxWidth": "100%"});

        
            var html_4e4dd6561afa8a572ca514520b16520c = $(`<div id="html_4e4dd6561afa8a572ca514520b16520c" style="width: 100.0%; height: 100.0%;">Year Built: 2001, Price:9.250.000, 118.0 m2 , ZipCode:2100 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_78e21367fc11335e95f6e660373302f8.setContent(html_4e4dd6561afa8a572ca514520b16520c);
        

        marker_f30793bbd5c10bcc4984381a7bd266a7.bindPopup(popup_78e21367fc11335e95f6e660373302f8)
        ;

        
    
    
            var marker_6a66068b35f1cb0ae2eaf38be62d3e97 = L.marker(
                [55.691662, 12.576608],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_55c01ed17cb099a5a5e15580c254b59a = L.popup({"maxWidth": "100%"});

        
            var html_0d1f4cb9728386676d2d0d39ca3b1b9c = $(`<div id="html_0d1f4cb9728386676d2d0d39ca3b1b9c" style="width: 100.0%; height: 100.0%;">Year Built: 1890, Price:9.995.000, 164.0 m2 , ZipCode:2100 ,  Rooms:5, HomeType:Ejerlejlighed</div>`)[0];
            popup_55c01ed17cb099a5a5e15580c254b59a.setContent(html_0d1f4cb9728386676d2d0d39ca3b1b9c);
        

        marker_6a66068b35f1cb0ae2eaf38be62d3e97.bindPopup(popup_55c01ed17cb099a5a5e15580c254b59a)
        ;

        
    
    
            var marker_d1ac8e8c4ba30cd376aa3c42f2151715 = L.marker(
                [55.7089397, 12.5885397],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_600d56ec9cbc0f28ce2b41964fb377b7 = L.popup({"maxWidth": "100%"});

        
            var html_f95e3272f567848ac0e8490dd9378f2a = $(`<div id="html_f95e3272f567848ac0e8490dd9378f2a" style="width: 100.0%; height: 100.0%;">Year Built: 1901, Price:21.750.000, 267.0 m2 , ZipCode:2100 ,  Rooms:7, HomeType:Ejerlejlighed</div>`)[0];
            popup_600d56ec9cbc0f28ce2b41964fb377b7.setContent(html_f95e3272f567848ac0e8490dd9378f2a);
        

        marker_d1ac8e8c4ba30cd376aa3c42f2151715.bindPopup(popup_600d56ec9cbc0f28ce2b41964fb377b7)
        ;

        
    
    
            var marker_86a60af942260a49e556aef965f4a47e = L.marker(
                [55.703306, 12.581145],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_b229cd7344dde110c0e03a143085383c = L.popup({"maxWidth": "100%"});

        
            var html_05e13c22f3c651d4d208dd2225836c71 = $(`<div id="html_05e13c22f3c651d4d208dd2225836c71" style="width: 100.0%; height: 100.0%;">Year Built: 1958, Price:4.700.000, 78.0 m2 , ZipCode:2100 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_b229cd7344dde110c0e03a143085383c.setContent(html_05e13c22f3c651d4d208dd2225836c71);
        

        marker_86a60af942260a49e556aef965f4a47e.bindPopup(popup_b229cd7344dde110c0e03a143085383c)
        ;

        
    
    
            var marker_242e3cfad270e9412c7d2c552917512f = L.marker(
                [55.709364, 12.564737],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_84834bceca8add2349f87e59d142ac67 = L.popup({"maxWidth": "100%"});

        
            var html_c41ca8b030b8fde66778f1efcc8f0221 = $(`<div id="html_c41ca8b030b8fde66778f1efcc8f0221" style="width: 100.0%; height: 100.0%;">Year Built: 1934, Price:3.500.000, 66.0 m2 , ZipCode:2100 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_84834bceca8add2349f87e59d142ac67.setContent(html_c41ca8b030b8fde66778f1efcc8f0221);
        

        marker_242e3cfad270e9412c7d2c552917512f.bindPopup(popup_84834bceca8add2349f87e59d142ac67)
        ;

        
    
    
            var marker_29532cb56ee58daeb4561376572a2d29 = L.marker(
                [55.703679, 12.586863],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_34633e6bc43e7006ef9f68e8af3ef6d5 = L.popup({"maxWidth": "100%"});

        
            var html_ded49b120938c87fe4b0f32de0712153 = $(`<div id="html_ded49b120938c87fe4b0f32de0712153" style="width: 100.0%; height: 100.0%;">Year Built: 1902, Price:5.100.000, 71.0 m2 , ZipCode:2100 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_34633e6bc43e7006ef9f68e8af3ef6d5.setContent(html_ded49b120938c87fe4b0f32de0712153);
        

        marker_29532cb56ee58daeb4561376572a2d29.bindPopup(popup_34633e6bc43e7006ef9f68e8af3ef6d5)
        ;

        
    
    
            var marker_1989251e3bdbb945a4aed44bdf1656fc = L.marker(
                [55.696682, 12.597544],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_eb7700872e5852e03b64f175a6ad9b2c = L.popup({"maxWidth": "100%"});

        
            var html_21e6a1ee8196b782b954f3a2a49d7979 = $(`<div id="html_21e6a1ee8196b782b954f3a2a49d7979" style="width: 100.0%; height: 100.0%;">Year Built: 1994, Price:5.750.000, 96.0 m2 , ZipCode:2100 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_eb7700872e5852e03b64f175a6ad9b2c.setContent(html_21e6a1ee8196b782b954f3a2a49d7979);
        

        marker_1989251e3bdbb945a4aed44bdf1656fc.bindPopup(popup_eb7700872e5852e03b64f175a6ad9b2c)
        ;

        
    
    
            var marker_7d235c156a285e26c2ed7366ce5a077e = L.marker(
                [55.707301, 12.58523],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_f9c6ac20ae82c774b5d23113fdab0dae = L.popup({"maxWidth": "100%"});

        
            var html_7974052f5498b17e1802c60a887585b1 = $(`<div id="html_7974052f5498b17e1802c60a887585b1" style="width: 100.0%; height: 100.0%;">Year Built: 1911, Price:6.500.000, 84.0 m2 , ZipCode:2100 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_f9c6ac20ae82c774b5d23113fdab0dae.setContent(html_7974052f5498b17e1802c60a887585b1);
        

        marker_7d235c156a285e26c2ed7366ce5a077e.bindPopup(popup_f9c6ac20ae82c774b5d23113fdab0dae)
        ;

        
    
    
            var marker_3ab815a7fb13bb720bfcef066a45227a = L.marker(
                [55.711573, 12.578328],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_7f2b8137b375c979037894bccd742bbf = L.popup({"maxWidth": "100%"});

        
            var html_27235a5e5005d625f05abbc28d542375 = $(`<div id="html_27235a5e5005d625f05abbc28d542375" style="width: 100.0%; height: 100.0%;">Year Built: 1938, Price:3.795.000, 68.0 m2 , ZipCode:2100 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_7f2b8137b375c979037894bccd742bbf.setContent(html_27235a5e5005d625f05abbc28d542375);
        

        marker_3ab815a7fb13bb720bfcef066a45227a.bindPopup(popup_7f2b8137b375c979037894bccd742bbf)
        ;

        
    
    
            var marker_a585688b7ecea2405a4a9a8e11126030 = L.marker(
                [55.696652, 12.574604],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_b75304bdb96264a02f9e7d48d1b89698 = L.popup({"maxWidth": "100%"});

        
            var html_28c4b653d08e3c8eb8a7385eb0f094a6 = $(`<div id="html_28c4b653d08e3c8eb8a7385eb0f094a6" style="width: 100.0%; height: 100.0%;">Year Built: 1886, Price:4.995.000, 72.0 m2 , ZipCode:2100 ,  Rooms:3, HomeType:Ejerlejlighed</div>`)[0];
            popup_b75304bdb96264a02f9e7d48d1b89698.setContent(html_28c4b653d08e3c8eb8a7385eb0f094a6);
        

        marker_a585688b7ecea2405a4a9a8e11126030.bindPopup(popup_b75304bdb96264a02f9e7d48d1b89698)
        ;

        
    
    
            var marker_3abdd608f4af6eda65f2d6d0f791f1d6 = L.marker(
                [55.697065, 12.585376],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_b25ce38b43e48dc57fd9e52de393b44e = L.popup({"maxWidth": "100%"});

        
            var html_ea157ba1b4aa158252c795c456851974 = $(`<div id="html_ea157ba1b4aa158252c795c456851974" style="width: 100.0%; height: 100.0%;">Year Built: 1891, Price:9.595.000, 133.0 m2 , ZipCode:2100 ,  Rooms:4, HomeType:Ejerlejlighed</div>`)[0];
            popup_b25ce38b43e48dc57fd9e52de393b44e.setContent(html_ea157ba1b4aa158252c795c456851974);
        

        marker_3abdd608f4af6eda65f2d6d0f791f1d6.bindPopup(popup_b25ce38b43e48dc57fd9e52de393b44e)
        ;

        
    
    
            var marker_28148953891554b61ff25091eb3b9224 = L.marker(
                [55.7144, 12.569815],
                {}
            ).addTo(marker_cluster_6acc92584669eaff7e446472dce773f4);
        
    
        var popup_dab07c019355a69555ca6fc60d039f72 = L.popup({"maxWidth": "100%"});

        
            var html_cd2190359da542f721cbc843786a8c42 = $(`<div id="html_cd2190359da542f721cbc843786a8c42" style="width: 100.0%; height: 100.0%;">Year Built: 1906, Price:2.995.000, 59.0 m2 , ZipCode:2100 ,  Rooms:2, HomeType:Ejerlejlighed</div>`)[0];
            popup_dab07c019355a69555ca6fc60d039f72.setContent(html_cd2190359da542f721cbc843786a8c42);
        

        marker_28148953891554b61ff25091eb3b92
