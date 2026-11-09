TRAIL RECOVERY RESEARCH 2027 v0.4
Prototipo offline/PWA de registro científico.
Incluye T0-T3, atleta por código, disciplina, bienestar, FC, datos de carrera, termografía (imagen y temperaturas manuales), algometría (3 lecturas y media), almacenamiento local, CSV y backup/restauración JSON.
El service worker/PWA requiere HTTPS y una primera carga online. Abrir index.html desde Files/Drive (file://) puede no habilitar el modo offline PWA.
LIMITACIONES: No existe backend, sincronización remota, cifrado local ni autenticación real de investigador. No introducir datos reales o identificables. El almacenamiento local puede borrarse y las imágenes ocupan espacio. Exportar backups JSON frecuentes.
Para producción: servidor seguro, cifrado en reposo y tránsito, acceso de atleta por código individual con diseño revisado, autenticación de investigador independiente, almacenamiento seguro de imágenes, sincronización con reintentos y resolución de conflictos, auditoría, backups cifrados, hosting UE, RGPD, consentimiento y aprobación ética.
