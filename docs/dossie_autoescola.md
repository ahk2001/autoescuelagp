# 📂 DOSSIÊ ESTRATÉGICO: AUTOESCUELA GP ALBACETE

> **Documento-fonte oficial para desenvolvimento do novo site de alta conversão.**  
> Todos os dados abaixo foram extraídos exclusivamente de fontes locais (`dados.txt`, `assets/`) e varredura pública (`autoescuelagp.com`, `maxitrailalbacete.com`, diretórios oficiais e registros públicos). Informações não localizadas publicamente estão sinalizadas como `[A CONFIRMAR COM O CLIENTE]`.

---

## 1. 🏢 DADOS INSTITUCIONAIS & CONTATO

* **Nome Comercial:** Autoescuela GP / GP Centro de Formación (e braço especializado em motociclismo: *Maxi Trail GP Albacete*)
* **Razão Social:** Centro de Formación y Autoescuela GP S.L.
* **CIF:** `[A CONFIRMAR COM O CLIENTE]`
* **Ano de Fundação:** 2013 / 2014 (meta description do site indica criação em 2013; texto da home e copyright indicam 2014)
* **Administrador / Instrutor Principal:** Gerardo Paños Fernández
* **Slogan Principal Sugerido (Espanhol):** *"Tu permiso de conducir en Albacete con enseñanza personalizada, tecnología táctil y máxima seguridad vial."*
* **Subtítulo Institucional (baseado no site atual):** *"Autoescuela GP es un centro de enseñanza de la conducción situado en Albacete, creado para ofrecer un servicio completo adaptado a cada alumno."*

### Canais de Contato
* **WhatsApp Principal (de `dados.txt`):** `+34 634 44 58 75` (`https://wa.me/34634445875`)
* **WhatsApp Secundário (informado no site oficial / Maxi Trail GP):** `+34 609 89 10 05` `[CONFIRMAR COM O CLIENTE QUAL NÚMERO PRIORIZAR NO BOTÃO FLUTUANTE]`
* **Telefone Fixo:** `+34 967 50 93 74`
* **E-mail Oficial:** `gp@autoescuelagp.com`
* **Site Oficial Atual:** `https://www.autoescuelagp.com/`
* **Site Complementar (Moto / Off-Road):** `https://maxitrailalbacete.com/cursos/`
* **Instagram:** [@autoescuelagpalbacete](https://www.instagram.com/autoescuelagpalbacete/)
* **Instagram Motoclub vinculado no rodapé:** [@motoclub_albacete](https://www.instagram.com/motoclub_albacete/)
* **Facebook:** [Auto Escuela GP Albacete](https://www.facebook.com/Auto-Escuela-GP-Albacete-562474333834492/)
* **Twitter/X:** [@autoescuelagpab](https://twitter.com/autoescuelagpab)

### Tom de Voz da Marca
* **Perfil:** Próximo, familiar, transparente, paciente e altamente técnico quando o assunto é segurança viária e pilotagem de motos.
* **Diferencial de Comunicação:** Transmite tranquilidade e confiança (especialmente relevante para alunos iniciantes e pessoas com *amaxofobia*), combinando experiência prática com modernidade tecnológica (aulas com telas táteis, test online AEOL e vídeos práticos).

---

## 2. 🎨 IDENTIDADE VISUAL E DESIGN SYSTEM

### Paleta de Cores (Extraída do `logo.png`, `favicon.png` e `style.css` oficial)

| Papel na Interface | Cor | Código HEX | Origem / Uso Recomendado |
| :--- | :--- | :--- | :--- |
| **Primária (Marca)** | Vermelho GP | `#DD0000` (variações no logo: `#FD0101` / `#BC0C06`) | Faixa vermelha do logotipo, fachada física e títulos/elementos de maior peso visual |
| **Secundária (Suporte)** | Cinza Metálico / Prata | `#9F9F9F` (variação no logo: `#C3C3C4`) | Barra superior do logotipo, divisores, bordas e badges técnicos |
| **Destaque / Conversão (CTA)** | Verde Ação / WhatsApp | `#398F14` (hover `#40A315`) ou `#25D366` | Botões principais de WhatsApp, CTAs de matrícula e confirmações |
| **Acento Secundário (Links/Info)** | Azul DGT / Institucional | `#003388` (`#038`) / `#3399CC` | Links informativos, placa "L" da fachada e avisos de resultados DGT |
| **Fundo Escuro (Dark Surface)** | Preto / Grafite Profundo | `#111111` / `#222222` | Seção Hero (sobre vídeo), rodapé e contrastes para o logotipo branco |
| **Fundo Claro (Light Surface)** | Branco / Cinza Gelo | `#FFFFFF` / `#F7F7F7` / `#E9E9E9` | Fundo principal das seções, cards de cursos e leitura confortável |
| **Texto Principal** | Grafite Escuro | `#222222` / `#333333` | Corpo de texto, listas de requisitos e descrições |

### Tipografia Recomendada
* **Títulos (Display / Headings):** `Oswald` (já presente no CSS original como `OswaldRegular`) ou `Montserrat` / `Outfit` em pesos Bold/SemiBold — reforça o caráter automobilístico e esportivo ("GP").
* **Corpo de Texto (Body / UI):** `Open Sans` (já utilizada no site atual: `OpenSansRegular`, `OpenSansSemibold`, `OpenSansBold`) ou `Inter` — excelente legibilidade em tabelas de requisitos DGT e mobile.

### Mapeamento Completo dos Arquivos em `assets/`

| Arquivo (Caminho Relativo) | Conteúdo Visual Observado | Uso Recomendado no Novo Site |
| :--- | :--- | :--- |
| `assets/logo.png` | Logotipo oficial "GP Autoescuela" com texto em branco e barras prata (`#C3C3C4`) + vermelha (`#FD0101`) | Cabeçalho (Header) sobre fundo escuro (`#111111`) ou barra de navegação escura; rodapé |
| `assets/favicon.png` | Ícone isolado das duas barras inclinadas (prata `#9F9F9F` + vermelha `#FC0101`) | Favicon do navegador, ícone de app/atalho e marcador visual de listas |
| `assets/homedesktop.mp4` | Vídeo em alta definição para desktop (4,37 MB) | Background animado do **Hero** em telas desktop (com overlay escuro para contraste) |
| `assets/homemobile.mp4` | Vídeo vertical/otimizado para mobile (5,50 MB) | Background animado do **Hero** em dispositivos móveis |
| `assets/estabelecimento.jpeg` | Foto noturna real da fachada de esquina ("GP Auto Escuela / Centro de Formación", placa "L", cartaz "Maxi Trail GP" e letreiro "Exams One") | Seção **Sobre Nós / Localização e Estrutura Física** (com alt text otimizado para Albacete) |
| `assets/9644b754-090a-4a22-ad79-60be636a0bdf.webp` | Motociclista com colete laranja de autoescola sobre moto BMW GS vermelha/preta em pista | Card **Permisos de Moto (A1 / A2 / A)** e destaque para práticas em pista |
| `assets/Captura de tela 2026-11-24 124806.png` | Aluno/piloto em BMW GS vermelha em pista asfaltada aberta | Galeria / Seção de **Aulas Práticas de Moto** |
| `assets/Captura de tela 2026-11-24 124818.png` | Piloto em BMW GS com cones de circuito ao fundo | Seção **Circuito Cerrado / Maniobras de Moto** |
| `assets/Captura de tela 2026-11-24 124834.png` | Piloto em pé nas pedaleiras sobre BMW GS próximo a cone amarelo (técnica Trail/Off-Road) | Seção **Maxi Trail GP / Perfeccionamiento** |
| `assets/Captura de tela 2026-11-24 124849.png` | Piloto com moto BMW F800GS branca identificada com adesivo "Auto Escuela GP" junto a rio/montanha | Card de **Rutas y Cursos On-Road / Off-Road** |
| `assets/Captura de tela 2026-11-24 124911.png` | Montagem espelhada com duas BMW GS e logotipo "GP Autoescuela" no topo | Banner promocional / Seção **Especialistas en Dos Ruedas** |
| `assets/Captura de tela 2026-11-24 125700.png` | Piloto em manobra radical (wheelie) com macacão azul ostentando patch "Auto Escuela GP" | Galeria / Destaque de **Alta Maestría en Conducción** |

---

## 3. 📍 SEDE FÍSICA, LOCALIZAÇÃO E HORÁRIOS

* **Endereço Completo:** Calle Imperial, 3 (esquina con Calle San Juan), 02006 Albacete, Castilla-La Mancha, España.
* **Coordenadas Geográficas (extraídas da URL do Maps):** `38.9824699, -1.8555974`
* **Link Direto do Google Maps:** [Ver Autoescuela GP en Google Maps](https://www.google.com/maps/place/Autoescuela+GP/@38.9824699,-1.8937062,14z/data=!4m10!1m2!2m1!1sautoescuela!3m6!1s0xd665fdca5a18353:0xdf60a8632c774a17!8m2!3d38.9824699!4d-1.8555974!15sCgthdXRvZXNjdWVsYVoNIgthdXRvZXNjdWVsYZIBDmRyaXZpbmdfc2Nob29smgEjQ2haRFNVaE5NRzluUzBWSlEwRm5TVVJ3Ym1SZlFrNUJFQUXgAQD6AQQIABBA!16s%2Fg%2F1pzpw9f1l)
* **Horários da Secretaria (registrados em diretórios locais — confirmar sazonalidade):**
  * **Segunda a Sexta (Lunes a Viernes):** 10:30 – 13:30 h | 17:30 – 20:30 h *(alguns diretórios apontam 17:00 – 20:00 h)* `[A CONFIRMAR COM O CLIENTE HORÁRIO EXATO ATUAL]`
  * **Sábados:** 10:00 – 13:30 h *(alguns registros listam fechado aos sábados)* `[A CONFIRMAR COM O CLIENTE]`
  * **Domingos:** Cerrado.

---

## 4. 🚗 CATÁLOGO EXAUSTIVO DE SERVIÇOS E CURSOS

### 4.1. Permisos Particulares
* **Permiso B (Coche / Turismo):**
  * Automóveis até 3.500 kg e até 9 lugares (incluído o condutor), com reboque de até 750 kg. Idade mínima: 18 anos.
  * *Nota sobre câmbio automático:* `[A CONFIRMAR COM O CLIENTE SE POSSUI VEÍCULO AUTOMÁTICO PARA PERMISO B]`
* **Permiso B+E / Autorización B-96 (Remolques):**
  * Turismos com reboque superior a 750 kg (B-96 até 4.250 kg de conjunto; EB quando supera os 4.250 kg dentro dos limites legais).
* **Permisos de Moto (AM, A1, A2, A):**
  * **Permiso AM (Ciclomotor):** Ciclomotores de 2 ou 3 rodas e quadriciclos até 50 c.c. Idade mínima: 15 anos.
  * **Permiso A1:** Motocicletas até 125 cm³. Idade mínima: 16 anos.
  * **Permiso A2:** Motocicletas com potência máxima de 35 kW. Idade mínima: 18 anos.
  * **Permiso A:** Motocicletas e triciclos de motor sem limite de potência (curso de 9h: 3h teórica prática, 2h pista, 4h circulação; solicitação com 10 dias úteis de antecedência). Idade mínima: 20 anos.
  * **Pista de Treino Própria Homologada:** O site informa práticas de pista/circuito fechado para motos e cursos *Maxi Trail GP*, porém não confirma expressamente se a pista é própria exclusiva ou compartilhada `[A CONFIRMAR COM O CLIENTE]`.

### 4.2. Cursos Oficiais DGT & Serviços Especiais
* **Recuperación de Puntos DGT (Parcial 12h / Total 24h):**
  * Não consta oferta direta como centro concessionário DGT homologado no site oficial `autoescuelagp.com`. `[A CONFIRMAR COM O CLIENTE SE IMPARTE OU APENAS ORIENTA/DERIVA ALUNOS]`
* **Amaxofobia (Miedo a Conducir):**
  * Serviço oficial listado em `/servicios/`: acompanhamento especializado para superar o medo ou angústia ao volante.
* **Clases de Reciclaje (Perfeccionamiento):**
  * Serviço oficial listado em `/servicios/`: aulas práticas para quem já possui carteira há muito tempo, não dirige regularmente ou deseja atualizar-se em normas e sinais.
* **Cursos Intensivos de Teórica & Plataforma Digital:**
  * Cursos intensivos de teórica sem custo adicional na matrícula (conforme FAQ do site), aulas com telas táteis, acesso a **Test On-Line AEOL** (`cloud.aeolservice.es`), **Vídeos Prácticas** (`gestionplus.aeolservice.es/videos`) e consulta direta de notas DGT.
* **Cursos Especializados de Moto (*Maxi Trail GP Albacete*):**
  * Cursos **Off-Road** (Iniciación e Avanzado), **Curso On-Road Personalizado o en Grupo** e **Rutas On-Road**.

### 4.3. Permisos Profesionales & Transporte
* **Permiso C (Camión):** Automóveis > 3.500 kg, até 9 lugares (idade mínima 21 anos, requer Permiso B).
* **Permiso C+E (Tráiler):** Conjunto de veículos acoplados com trator categoria C e reboque > 750 kg (idade mínima 21 anos, requer Permiso C).
* **Permiso D (Autobús):** Transporte de pessoas com mais de 9 lugares (idade mínima 21 anos, requer Permiso B).
* **CAP (Certificado de Aptitud Profesional):** Listado oficialmente em `/servicios/` com referência ao *R.D. 1032/2009* do Ministerio de Transporte. *(Especificar modalidades vigentes — Inicial 140h / Continuo 35h — `[A CONFIRMAR COM O CLIENTE]`)*.
* **ADR (Mercancías Peligrosas), Carretillas Elevadoras e Tacógrafo Digital:** Não constam listados no site atual. `[A CONFIRMAR COM O CLIENTE]`

### 4.4. Credenciamentos (LABORA / FUNDAE)
* **Centro LABORA:** Não aplicável diretamente como marca valenciana (a escola fica em **Albacete / Castilla-La Mancha**, onde o equivalente seria JCCM / SEPE). Não há menção a cursos subvencionados no site. `[A CONFIRMAR COM O CLIENTE]`
* **Formação Bonificada FUNDAE:** Não consta menção explícita no site atual. `[A CONFIRMAR COM O CLIENTE SE TRAMITA BONIFICAÇÃO FUNDAE PARA EMPRESAS/CAP]`

---

## 5. 💰 ESTRUTURA COMERCIAL E TARIFAS

### Tarifas Confirmadas Publicamente (via `maxitrailalbacete.com/cursos/`)
* **Curso para el Permiso A (DGT 9h):** **350 €**
* **Curso Maxi Trail GP — Iniciación (9:00 a 14:00, máx. 10 alumnos):** **120 €** *(reserva mínima 50 €; comida opcional 15 €)*
* **Curso Maxi Trail GP — Avanzado (9:00 a 14:00, máx. 10 alumnos):** **140 €** *(reserva mínima 50 €; comida opcional 15 €)*
* **Curso On-Road Personalizado o en Grupo:** **Desde 120 €**
* **Ruta On-Road Solidaria SAMPO (~400 km):** **60 € piloto / 30 € acompañante**

### Tarifas de Permisos Gerais (B, AM, A1, A2, C, C+E, D, Reciclaje, Amaxofobia)
* O site oficial `autoescuelagp.com` não publica tabela de preços para matrícula do Permiso B, pacotes de aulas práticas ou taxas da DGT (as aulas práticas têm duração oficial de **45 minutos**, conforme FAQ).
* **Exibição recomendada no site:** `"Consultar tarifa actualizada y bonos por WhatsApp"` `[VALORES EXATOS A CONFIRMAR COM O CLIENTE]`.
* **Modalidades de Pagamento:** `[A CONFIRMAR COM O CLIENTE — ex.: Efectivo, Tarjeta, Bizum, Financiación]`

---

## 6. ⭐ PROVA SOCIAL, REPUTAÇÃO E DEPOIMENTOS

* **Nota Média Verificada:** Entre **4,7 e 5,0 / 5 estrellas** nos diretórios locais consultados (*MejoresAutoescuelas.net*: **4,8 / 5**; *Trustlocal*: >8,5/10 com mais de 50 avaliações registradas).
* **Nota e Total Exato no Google Reviews:** `[A CONFIRMAR COM O CLIENTE / EXTRAIR DO PAINEL DO GOOGLE MAPS]`
* **Instrutores Nominalmente Elogiados:**
  * **Gerardo Paños Fernández** — citado recorrentemente nas avaliações por sua paciência, trato próximo e familiar, explicações claras e aulas práticas tranquilas que reduzem o nervosismo ao volante.
* **Síntese Fática dos Pontos Mais Elogiados nas Resenhas Públicas (`autoescuelaespana24.com`, `trustlocal.es`, `maptons.com`):**
  1. Paciência e calma dos professores durante as aulas práticas.
  2. Trato humano, familiar e transparente no atendimento de secretaria e gestão de horários.
  3. Eficácia na preparação para o exame teórico (telas táteis + cursos intensivos) e prático.
  4. Apoio real para alunos com nervosismo ou medo de dirigir (*amaxofobia*).
* **Transcrições Literais de 4 a 6 Depoimentos Reais do Google Maps:**
  * *Nota de integridade:* A consulta sem navegador automatizado não retornou o texto integral literal das resenhas individuais do Google Maps. Para manter **zero alucinação**, as citações literais devem ser coletadas diretamente pelo cliente ou via exportação do Perfil da Empresa no Google: `[A CONFIRMAR / INSERIR 4 A 6 RESEÑAS LITERALES DEL PERFIL DE GOOGLE MAPS]`.

---

## 7. 📲 ARQUITETURA DE CONVERSÃO & LINKS DE WHATSAPP

Todos os links abaixo utilizam o WhatsApp principal informado em `dados.txt` (`+34 634 44 58 75`) com mensagens pré-configuradas em **Espanhol da Espanha (Castellano)**:

1. **Matrícula Geral / Permiso B (Coche):**
   * **Texto:** `¡Hola! Me gustaría recibir información sobre precios, horarios y matrícula para el Permiso B en Autoescuela GP Albacete.`
   * **Link:** `https://wa.me/34634445875?text=%C2%A1Hola!%20Me%20gustar%C3%ADa%20recibir%20informaci%C3%B3n%20sobre%20precios%2C%20horarios%20y%20matr%C3%ADcula%20para%20el%20Permiso%20B%20en%20Autoescuela%20GP%20Albacete.`

2. **Permisos de Moto (AM / A1 / A2 / A) & Cursos Maxi Trail GP:**
   * **Texto:** `¡Hola! Quiero informarme sobre los permisos de moto (AM, A1, A2, A) o los cursos de conducción en Autoescuela GP.`
   * **Link:** `https://wa.me/34634445875?text=%C2%A1Hola!%20Quiero%20informarme%20sobre%20los%20permisos%20de%20moto%20(AM%2C%20A1%2C%20A2%2C%20A)%20o%20los%20cursos%20de%20conducci%C3%B3n%20en%20Autoescuela%20GP.`

3. **Cursos Profissionais (CAP / Camión C / Tráiler C+E / Autobús D):**
   * **Texto:** `¡Hola! Necesito información sobre los permisos profesionales (C, C+E, D) y cursos CAP en Autoescuela GP.`
   * **Link:** `https://wa.me/34634445875?text=%C2%A1Hola!%20Necesito%20informaci%C3%B3n%20sobre%20los%20permisos%20profesionales%20(C%2C%20C%2BE%2C%20D)%20y%20cursos%20CAP%20en%20Autoescuela%20GP.`

4. **Aulas Práticas de Reciclagem / Superação de Amaxofobia:**
   * **Texto:** `¡Hola! Ya tengo el carné pero me gustaría consultar por clases de reciclaje o apoyo para perder el miedo a conducir.`
   * **Link:** `https://wa.me/34634445875?text=%C2%A1Hola!%20Ya%20tengo%20el%20carn%C3%A9%20pero%20me%20gustar%C3%ADa%20consultar%20por%20clases%20de%20reciclaje%20o%20apoyo%20para%20perder%20el%20miedo%20a%20conducir.`

5. **Consulta sobre Recuperación de Puntos DGT (caso o cliente confirme oferta/parceria):**
   * **Texto:** `¡Hola! Quisiera consultar información y próximas fechas sobre recuperación de puntos DGT en Albacete.`
   * **Link:** `https://wa.me/34634445875?text=%C2%A1Hola!%20Quisiera%20consultar%20informaci%C3%B3n%20y%20pr%C3%B3ximas%20fechas%20sobre%20recuperaci%C3%B3n%20de%20puntos%20DGT%20en%20Albacete.`

---

## 8. 📐 DIRETRIZES RECOMENDADAS PARA A CRIAÇÃO DO SITE

### Proposta Única de Valor (UVP) em Albacete
> **En Espanhol (para uso no Hero):** *"Sácate el carné en Albacete con trato cercano, aulas táctiles y formación experta en coche, moto y vehículos profesionales."*  
> **Diferenciais reais para destacar:** Mais de 10 anos de trajetória em Albacete (desde 2013/2014), referência local em duas rodas (*Maxi Trail GP*), atendimento humano liderado por Gerardo Paños, cursos intensivos de teórica sem custo adicional, plataforma AEOL (testes e vídeos) e atendimento especializado para *amaxofobia* e *reciclaje*.

### Arquitetura de Seções Recomendada (Ordem de Alta Conversão)
1. **Header Fixo (Dark `#111111`):** `assets/logo.png` à esquerda + menu limpo (*Permisos*, *Profesionales*, *Motos & Trail*, *Amaxofobia*, *Contacto*) + botão CTA verde de WhatsApp (`634 44 58 75`).
2. **Hero Full-Screen com Vídeo Background:** `assets/homedesktop.mp4` (desktop) e `assets/homemobile.mp4` (mobile) com overlay escuro, H1 de alto impacto, selo de avaliação 4.8★+ e dois CTAs: *"Quiero Matricularme (WhatsApp)"* e *"Ver Permisos"*.
3. **Barra de Credibilidade & Acesso Rápido do Aluno:** Links diretos para *Test On-Line AEOL*, *Vídeos de Prácticas* e *Consulta de Notas DGT* (funcionalidade muito valorizada pelos alunos atuais).
4. **Grid de Permisos Particulares:** Cards para **Permiso B**, **Motos (AM, A1, A2, A)** e **Remolques (B+E / B-96)** com idade mínima, requisitos resumidos e botão WhatsApp específico.
5. **Bloco Diferencial "Especialistas en Dos Ruedas — Maxi Trail GP":** Usando as fotos reais das BMW GS da pasta `assets/` com destaque para o curso do Permiso A (350 €) e cursos On-Road / Off-Road (desde 120 €).
6. **Permisos Profesionales & Servicios Especiales:** Tabs ou cards separados para **Camión C / Tráiler C+E / Autobús D / CAP** e um bloco empático dedicado a **Amaxofobia & Clases de Reciclaje**.
7. **Prova Social (Google Reviews):** Nota média em destaque + menção a Gerardo e à equipe + espaço pronto para inserir as 4–6 resenhas literais confirmadas.
8. **Estrutura Física, Horários e Mapa:** Foto da fachada (`assets/estabelecimento.jpeg`), endereço completo (`C/ Imperial, 3, 02006 Albacete`), horários e botão *"Cómo llegar en Google Maps"*.
9. **FAQ Enxuto & Footer Completo:** Perguntas frequentes reais extraídas do site (duração de 45 min das aulas, exame teórico de 30 perguntas, cursos intensivos gratuitos) + botão flutuante de WhatsApp.
