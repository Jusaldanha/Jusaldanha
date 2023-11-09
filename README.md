<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <title>Mapa Mental - Canais de Marketing Digital</title>
  <link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/npm/mindmap@1.0.1/dist/style.css">
</head>
<body>
  <div id="map"></div>

  <script src="https://cdn.jsdelivr.net/npm/mindmap@1.0.1/dist/index.js"></script>
  <script>
    // Configuração do mapa mental
    const mapConfig = {
      root: "Canais de Marketing Digital",
      data: [
        { id: "1", root: "Canais de Marketing Digital", topic: "Marketing de Conteúdo" },
        { id: "2", root: "Canais de Marketing Digital", topic: "Mídias Sociais" },
        { id: "3", root: "Canais de Marketing Digital", topic: "Email Marketing" },
        { id: "4", root: "Canais de Marketing Digital", topic: "Publicidade Online" },
        { id: "5", root: "Canais de Marketing Digital", topic: "SEO" },
        { id: "6", root: "Canais de Marketing Digital", topic: "Marketing de Influência" },
        { id: "7", root: "Canais de Marketing Digital", topic: "Marketing de Afiliados" },
        { id: "8", root: "Canais de Marketing Digital", topic: "Marketing de Busca" },
        { id: "9", root: "Canais de Marketing Digital", topic: "Marketing de Vídeo" }
      ],
      container: document.getElementById("map"),
    };

    // Inicializar o mapa mental
    const map = new mindmap.Mindmap(mapConfig);
    map.init();
  </script>
</body>
</html>
