# Venta
Compra y venta 
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Repuestos JD</title>
    <style>
        body { font-family: sans-serif; text-align: center; background-color: #f0f2f5; margin: 0; padding-bottom: 50px; }
        .header { background-color: #1c1e21; color: white; padding: 20px 0; margin-bottom: 20px; }
        .logo-img { width: 90px; height: 90px; border-radius: 50%; border: 3px solid white; object-fit: cover; }
        .contenedor { display: flex; flex-direction: column; gap: 20px; align-items: center; }
        .producto { background: white; padding: 15px; border-radius: 12px; box-shadow: 0 4px 6px rgba(0,0,0,0.1); width: 85%; max-width: 320px; }
        .prod-img { width: 100%; border-radius: 8px; height: 200px; object-fit: cover; background-color: #eee; }
        .precio { font-size: 1.4em; color: #28a745; font-weight: bold; margin: 10px 0; }
        .btn-whatsapp { display: block; background-color: #25D366; color: white; padding: 12px; text-decoration: none; border-radius: 8px; font-weight: bold; margin-top: 10px; }
        .pago-info { background: #ffffff; margin: 20px auto; padding: 15px; border-radius: 12px; border: 2px dashed #007bff; width: 85%; max-width: 320px; }
        .tarjeta-box { background: #e7f3ff; padding: 10px; border-radius: 5px; font-family: monospace; font-size: 1.1em; color: #007bff; margin: 10px 0; border: 1px solid #b3d7ff; }
        .btn-copiar { background-color: #007bff; color: white; border: none; padding: 10px; border-radius: 5px; width: 100%; font-weight: bold; cursor: pointer; }
    </style>
</head>
<body>

    <div class="header">
        <img src="https://i.ibb.co/prrd6F1y/Screenshot-20260117-133946-Facebook.jpg" alt="Logo" class="logo-img">
        <h1 style="margin:10px 0 5px;">REPUESTOS JD</h1>
    </div>

    <div class="contenedor">
        <div class="producto">
            <img src="https://i.ibb.co/zv8FqBW/IMG-20251216-WA0664-1.jpg" alt="Compresor" class="prod-img">
            <h2>Compresor de Aire</h2>
            <div class="precio">$40</div>
            <a href="https://wa.me/5351288111?text=Hola, quiero el Compresor ($40)" class="btn-whatsapp">Pedir por WhatsApp</a>
        </div>

        <div class="producto">
            <img src="https://i.ibb.co/hFCDXWyv/IMG-20260111-WA0258.jpg" alt="Inversor" class="prod-img">
            <h2>Inversor de Corriente</h2>
            <div class="precio">$105</div>
            <a href="https://wa.me/5351288111?text=Hola, quiero el Inversor ($105)" class="btn-whatsapp">Pedir por WhatsApp</a>
        </div>

        <div class="producto">
            <img src="https://i.ibb.co/1G62cBLV/IMG-20251228-WA0317.jpg" alt="Arrancador" class="prod-img">
            <h2>Arrancador de Motor</h2>
            <div class="precio">$95</div>
            <a href="https://wa.me/5351288111?text=Hola, quiero el Arrancador ($95)" class="btn-whatsapp">Pedir por WhatsApp</a>
        </div>

        <div class="producto">
            <img src="https://i.ibb.co/L6V2M8f/qFFycZHG.jpg" alt="Cargador" class="prod-img">
            <h2>Cargador de Batería</h2>
            <div class="precio">$60</div>
            <a href="https://wa.me/5351288111?text=Hola, quiero el Cargador ($60)" class="btn-whatsapp">Pedir por WhatsApp</a>
        </div>
    </div>

    <div class="pago-info">
        <h3>💳 Pago: Transfermóvil</h3>
        <div class="tarjeta-box" id="numTarjeta">9227959873913516</div>
        <button class="btn-copiar" onclick="copiar()">Copiar Tarjeta</button>
    </div>

    <script>
        function copiar() {
            var el = document.createElement('textarea');
            el.value = "9227959873913516";
            document.body.appendChild(el);
            el.select();
            document.execCommand('copy');
            document.body.removeChild(el);
            alert("¡Copiado! Ya puedes pegarlo en Transfermóvil");
        }
    </script>

</body>
</html>
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Repuestos JD</title>
    <style>
        body { font-family: sans-serif; text-align: center; background-color: #f0f2f5; margin: 0; padding-bottom: 50px; }
        .header { background-color: #1c1e21; color: white; padding: 20px 0; margin-bottom: 20px; }
        .logo-img { width: 90px; height: 90px; border-radius: 50%; border: 3px solid white; object-fit: cover; }
        .contenedor { display: flex; flex-direction: column; gap: 20px; align-items: center; }
        .producto { background: white; padding: 15px; border-radius: 12px; box-shadow: 0 4px 6px rgba(0,0,0,0.1); width: 85%; max-width: 320px; }
        .prod-img { width: 100%; border-radius: 8px; height: 200px; object-fit: cover; background-color: #eee; }
        .precio { font-size: 1.4em; color: #28a745; font-weight: bold; margin: 10px 0; }
        .btn-whatsapp { display: block; background-color: #25D366; color: white; padding: 12px; text-decoration: none; border-radius: 8px; font-weight: bold; margin-top: 10px; }
        .pago-info { background: #ffffff; margin: 20px auto; padding: 15px; border-radius: 12px; border: 2px dashed #007bff; width: 85%; max-width: 320px; }
        .tarjeta-box { background: #e7f3ff; padding: 10px; border-radius: 5px; font-family: monospace; font-size: 1.1em; color: #007bff; margin: 10px 0; border: 1px solid #b3d7ff; }
        .btn-copiar { background-color: #007bff; color: white; border: none; padding: 10px; border-radius: 5px; width: 100%; font-weight: bold; cursor: pointer; }
    </style>
</head>
<body>

    <div class="header">
        <img src="https://i.ibb.co/prrd6F1y/Screenshot-20260117-133946-Facebook.jpg" alt="Logo" class="logo-img">
        <h1 style="margin:10px 0 5px;">REPUESTOS JD</h1>
    </div>

    <div class="contenedor">
        <div class="producto">
            <img src="https://i.ibb.co/zv8FqBW/IMG-20251216-WA0664-1.jpg" alt="Compresor" class="prod-img">
            <h2>Compresor de Aire</h2>
            <div class="precio">$40</div>
            <a href="https://wa.me/5351288111?text=Hola, quiero el Compresor ($40)" class="btn-whatsapp">Pedir por WhatsApp</a>
        </div>

        <div class="producto">
            <img src="https://i.ibb.co/hFCDXWyv/IMG-20260111-WA0258.jpg" alt="Inversor" class="prod-img">
            <h2>Inversor de Corriente</h2>
            <div class="precio">$105</div>
            <a href="https://wa.me/5351288111?text=Hola, quiero el Inversor ($105)" class="btn-whatsapp">Pedir por WhatsApp</a>
        </div>

        <div class="producto">
            <img src="https://i.ibb.co/1G62cBLV/IMG-20251228-WA0317.jpg" alt="Arrancador" class="prod-img">
            <h2>Arrancador de Motor</h2>
            <div class="precio">$95</div>
            <a href="https://wa.me/5351288111?text=Hola, quiero el Arrancador ($95)" class="btn-whatsapp">Pedir por WhatsApp</a>
        </div>

        <div class="producto">
            <img src="https://i.ibb.co/L6V2M8f/qFFycZHG.jpg" alt="Cargador" class="prod-img">
            <h2>Cargador de Batería</h2>
            <div class="precio">$60</div>
            <a href="https://wa.me/5351288111?text=Hola, quiero el Cargador ($60)" class="btn-whatsapp">Pedir por WhatsApp</a>
        </div>
    </div>

    <div class="pago-info">
        <h3>💳 Pago: Transfermóvil</h3>
        <div class="tarjeta-box" id="numTarjeta">9227959873913516</div>
        <button class="btn-copiar" onclick="copiar()">Copiar Tarjeta</button>
    </div>

    <script>
        function copiar() {
            var el = document.createElement('textarea');
            el.value = "9227959873913516";
            document.body.appendChild(el);
            el.select();
            document.execCommand('copy');
            document.body.removeChild(el);
            alert("¡Copiado! Ya puedes pegarlo en Transfermóvil");
        }
    </script>

</body>
</html>
