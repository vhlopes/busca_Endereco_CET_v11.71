# 🗺️ buscaEndereco_CET_v11.71  
**Sistema de Geocodificação e Enriquecimento de Endereços – CET-SP**  
Versão: 11.71  
Autor: **Vitor Henrique Leal Lopes Braz**  

---

## 📘 Sobre o Projeto  
Este projeto implementa um sistema de **geocodificação e enriquecimento de endereços** voltado para a cidade de São Paulo.  
O código integra bases internas da **CET-SP** e serviços **GIS (GeoServer)**, permitindo transformar endereços textuais em coordenadas geográficas e adicionar informações administrativas (GET, DET, Subprefeitura, Distrito, Região e Classificação Viária).  

A aplicação foi desenvolvida em **Python**, com foco em **tratamento de dados espaciais**, **normalização de endereços** e **integração com serviços de geoprocessamento**.

---

## ⚙️ Principais Funcionalidades  
- 🔹 Normalização e enriquecimento de endereços  
- 🔹 Geocodificação via API interna da CET-SP  
- 🔹 Consultas espaciais via GeoServer (WMS/GetFeatureInfo)  
- 🔹 Fallback inteligente com busca por similaridade (TF-IDF)  
- 🔹 Identificação automática de marginais e rodovias  
- 🔹 Determinação de circunscrição (SP / fora de SP)

---

## 🧩 Tecnologias Utilizadas  
- 🐍 **Python 3.x**  
- 📊 **Pandas / GeoPandas / Shapely**  
- 🌐 **Requests / XML / Regex**  
- 🧠 **TF-IDF Similarity (Scikit-learn)**  
- 🗺️ **GeoServer / GIS Integration**

---

## 🚀 Como Executar  
> ⚠️ Este projeto depende de APIs internas da CET-SP, atualmente inacessíveis fora do ambiente corporativo.  
> O código está disponível para fins de **estudo, portfólio e demonstração técnica**.

Para fins didáticos, a estrutura pode ser adaptada para APIs públicas de geocodificação, como:
- Google Maps Geocoding API  
- Nominatim (OpenStreetMap)

---

## 🧾 Documentação  
Toda a documentação técnica está disponível no arquivo:  
📄 `DOCUMENTACAO_buscaEndereco_CET_v11_71.txt`

---

## 💡 Autor  
**Vitor Henrique Leal Lopes Braz**  
Data Analyst | Python | GIS | Machine Learning  

🔗 [LinkedIn](https://www.linkedin.com/in/vitor-henrique-leal-lopes-braz)  
