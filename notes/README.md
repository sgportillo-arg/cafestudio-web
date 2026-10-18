# Café Studio: relevamiento del sitio actual (18-10-2026)

## DNS (consultado vía dns.google)
- NS: ns3.hostmar.com, ns4.hostmar.com (Hostmar; no es DonWeb ni Cloudflare)
- A @: 103.169.142.0 · www: CNAME a cafestudio.com.ar
- MX: Google Workspace (aspmx.l.google.com + alt1-4)
- TXT: SPF `v=spf1 include:_spf.google.com include:spf.sendinblue.com ~all`, brevo-code, canva-domain-verify
- Al migrar hay que conservar MX, SPF y el TXT de Brevo.

## Estructura del sitio actual (Canva, una sola página)
Menú: Trabajos · Acerca de · Servicios · Contactar · "Suscribite al news de neuromarketing". CTA "Agendá un análisis gratuito".

## Textos
- Hero: "CAFÉ STUDIO" · "Transformamos emociones en decisiones".
- Intro: trabajaron con marcas y organizaciones de salud, gastronomía y construcción civil, entre otros, en branding, gestión estratégica de comunicación, capacitaciones y conferencias. Se presentan como "empresa líder en neuromarketing aplicado a la comunicación y las marcas".
- Portfolio "Ilustraciones y Brand": piezas para El Polo (heladería, "desde 1960") + ilustraciones/personajes. Sección "Nuestros clientes" sin contenido legible.
- "Lo más importante": Conectar con la emoción · Atreverse a lo incómodo · Trabajar con sentido estratégico · Ejecutar con alma.
- Acerca de: agencia de neuromarketing y comunicación estratégica que transforma puntos de dolor en oportunidades; estrategias basadas en investigación y neurociencia; "las ideas se convierten en estrategia y la estrategia en decisión".
- Valores C.A.F.É.: C Consciencia · A Atención · F Feeling (emoción) · E Ejecutar. **Error en el sitio actual: el texto de F repite el de A**.
- Servicios: Consultorías integrales · Branding/Ilustraciones · Gestión estratégica de redes · Capacitaciones.
- Método C.A.F.É.: "Una herramienta diseñada para ordenar, decidir y accionar". Foco en prioridades, comunicación, delegación de tareas y estrategias de neuromarketing aplicables.
- Contacto: info@cafestudio.com.ar · Argentina.

## Del portfolio (/workspace/portfolio.txt)
Servicios: branding/rebranding, marketing y comunicación, consultoría, capacitaciones (neuromarketing/neuroventas, comunicación empresarial, comunicación no conflictiva, gestión de redes). Capacitaciones: AWS All Hands (abr 2024), RomiPack y FunPack, Municipalidad de Corrientes (may 2022), Expo Franquicias 2023. Visión, misión y método de 4 pasos. El portfolio trae el WhatsApp viejo (3794001375): no usar.

## Estilo
- Fondo de papel beige con textura (assets/papel.jpg), tipografía display condensada gris muy grande (estilo Oswald/Anton), sans geométrica con itálicas para el claim, mucho gris/negro.
- Acentos de color en las ilustraciones (coral de El Polo, multicolor). En el CSS aparecen #f5f0ea, #faf1ea, #323232, #856550, #f76b4c, #f57b33.
- Logo: "Café Studio" negro con barra (assets/logo.webp). Ilustración de mano con taza (assets/taza.webp).
- Tipografías exactas no legibles (Canva las renderiza por script).

## Assets descargados (del propio sitio, optimizados)
logo, taza, ilustracion-mente, ilustracion-chica, personajes, elpolo-casa-central, elpolo-sello, elpolo-logo, papel, favicon. Captura: sitio-actual.png. Texto completo: texto-sitio-actual.txt.
