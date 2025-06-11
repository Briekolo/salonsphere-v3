# SalonSphere

Een moderne salon management applicatie gebouwd met Next.js en Supabase.

## Functionaliteiten

- Dashboard voor overzicht
- Klantenbeheer
- Afspraken planning
- Behandelingen beheer
- Voorraad beheer
- Marketing tools

## Technologieën

- **Frontend**: Next.js 15, React 19, TypeScript
- **Backend**: Supabase
- **UI**: Lucide React icons
- **Styling**: Tailwind CSS (te configureren)
- **Deployment**: Vercel

## Lokale ontwikkeling

```bash
# Dependencies installeren
npm install

# Development server starten
npm run dev

# Productie build maken
npm run build

# Productie server starten
npm start
```

## Environment variabelen

Maak een `.env.local` bestand aan met:

```
NEXT_PUBLIC_SUPABASE_URL=je_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=je_supabase_anon_key
```

## Deployment

Dit project is geoptimaliseerd voor deployment op Vercel. 