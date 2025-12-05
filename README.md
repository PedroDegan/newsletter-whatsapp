# 📡 Newsletter Tech WhatsApp

Um projeto que envia diariamente uma newsletter de tecnologia via WhatsApp.
As notícias são coletadas automaticamente usando Selenium (web scraping).

## 🚀 Funcionalidades
- Coleta automática de manchetes de tecnologia
- Formatação de newsletter
- Envio via WhatsApp Cloud API
- (futuro) Seleção inteligente de notícias

## 📁 Estrutura do projeto
- `src/scraper.py` — web scraping
- `src/newsletter.py` — formatação da newsletter
- `src/whatsapp_api.py` — integração com WhatsApp API
- `tests/` — testes automatizados

## 🔧 Instalação

```bash
pip install -r requirements.txt
