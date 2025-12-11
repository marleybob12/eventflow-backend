# EventFlow API

Backend API para o sistema EventFlow

## Endpoints

- `POST /api/comprar-ingresso` - Compra ingresso e envia email
- `POST /api/dados-compra` - Cria ingresso (sem email)
- `POST /api/validar-qrcode` - Valida QR Code na entrada
- `GET /api/listar-ingressos?usuarioID=xxx` - Lista ingressos do usuário

## Deploy

bash
# Instalar Vercel CLI
npm i -g vercel

# Deploy
vercel --prod


## Variáveis de Ambiente

Configure no Vercel Dashboard:
- FIREBASE_SERVICE_ACCOUNT
- GMAIL_EMAIL
- GMAIL_SENHA
- FRONTEND_URL