# 🗺️ App de Localização

Aplicativo mobile criado com **Expo + React Native** para demonstrar funcionalidades de geolocalização, geocodificação e armazenamento em **Supabase**, além de comparar duas APIs de mapas: **Google Maps** e **Mapbox**.

---

## 🎯 Objetivo

- Obter a localização atual do usuário via GPS.  
- Fazer geocodificação direta (endereço → coordenadas) usando Google, Mapbox e Nominatim (OSM).  
- Exibir mapas com marcadores (Google / OSM via UrlTile / Mapbox).  
- Salvar e listar locais no Supabase.  
- Produzir um comparativo prático entre Google Maps e Mapbox.  

---

## 🧩 Tecnologias

- **Expo + React Native**  
- **expo-location** (GPS / permissões)  
- **react-native-maps** (renderização dos mapas)  
- **axios** (requisições HTTP)  
- **Supabase** (backend e banco de dados)  
- **Google Maps API** (Geocoding / Maps)  
- **Mapbox** (Geocoding / Maps)  
- **Nominatim / OpenStreetMap** (geocoding grátis, uso limitado)  

---

## 🌍 Comparativo: Google Maps vs Mapbox

| **Recurso** | **Google Maps** | **Mapbox** |
|--------------|-----------------|-------------|
| **Licença** | Pago (uso gratuito limitado) | Gratuito para uso básico / plano flexível |
| **Personalização do mapa** | Limitada | Altamente personalizável (cores, camadas) |
| **APIs para desenvolvedores** | Extensas, porém mais restritas | Extensas e abertas |
| **Modo offline** | Limitado | Melhor suporte |
| **Integração com React Native** | Via bibliotecas de terceiros | Suporte oficial (`react-native-mapbox-gl`) |
| **Atualização de dados** | Atualizações frequentes e automáticas | Atualizações via API customizáveis |
| **Foco principal** | Navegação e localização | Visualização de dados e personalização |
| **Custo por uso intensivo** | Mais alto | Mais acessível |

---
