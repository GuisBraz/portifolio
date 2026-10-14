# Guilherme dos Santos Braz — Portfólio

**Técnico de Processos em Caldeiraria e Usinagem · Graduando em Engenharia Mecânica · Desenvolvedor de software industrial**

Planejo a fabricação de equipamentos pesados para mineração e siderurgia, e construo as ferramentas de software que tornam esse planejamento mais rápido.

[LinkedIn](https://www.linkedin.com/in/guilherme-santos-66b8162a0) · [GitHub](https://github.com/GuisBraz) · Contagem, MG

---

## Sobre

Meu trabalho começa no desenho técnico e termina no chão de fábrica. Interpreto projetos de caldeiraria pesada, monto listas de materiais, detalho peças em CAD para programação de corte no Lantek, emito requisições de compra e ordens de produção e dou suporte técnico a caldeireiros, montadores e soldadores.

No meio desse fluxo, percebi que muitas tarefas repetitivas podiam virar software. Assim nasceram as ferramentas deste portfólio, todas criadas a partir de problemas reais da produção. De forma independente, também desenvolvo projetos mecânicos, do conceito ao cálculo estrutural.

## Experiência

| Período | Cargo | Empresa |
|---|---|---|
| jun/2025 – atual | Técnico de Processos — Caldeiraria e Usinagem | Sofir do Brasil Construções Industriais |
| dez/2023 – mai/2025 | Auxiliar de Programação de Produção III → II (PCP) | Sofir do Brasil Construções Industriais |
| ago/2022 – out/2022 | Auxiliar de Eletricista | SWE Engenharia Elétrica e Automação |
| jul/2019 – jul/2021 | Aprendiz Industrial | Belgo Bekaert Arames |

## Formação

- **Engenharia Mecânica** — IFMG *(em andamento)*
- **Técnico em Eletrotécnica** — CEFET-MG *(concluído)*

## Projetos de engenharia

### TC-2025-01 · Suporte articulado para condensadora
Projeto independente. Suporte de fachada que gira 180° em torno de um pivô central, alternando entre posição de trabalho e de manutenção, sem andaime nem trabalho em altura fora da estrutura.

- Modelagem 3D e conjunto soldado no Inventor, com desenhos de fabricação em A3
- Carga de vento pela NBR 6123 (140 km/h) nas duas orientações do equipamento
- Análise de tensões em quatro casos de carga, com contato pino-bucha
- Trava tipo baioneta para fixar a plataforma em 0° e 180°
- Memória de cálculo e apresentação 3D interativa para o cliente

`Inventor` `Análise de tensões` `NBR 6123` `ASTM A36` `SAE 1020` `Three.js`

> Projeto e cálculo de minha autoria; liberação final com ART de engenheiro habilitado.

## Projetos de software

### PROJTEC 1D — otimização de corte linear · *produto comercial*
Calcula o melhor aproveitamento de barras e perfis (First-Fit Decreasing), controla sobras em estoque, gera relatório em PDF vetorial e imprime etiquetas direto na Zebra ZD220. Histórico de trabalhos por commessa, numeração automática de RCs, uso simultâneo em rede local, login, licenciamento e pagamentos.

`Python` `PySide6` `Supabase` `Vercel` `Mercado Pago` `ZPL` `Inno Setup` · [Versões publicadas](https://github.com/GuisBraz/projtec1d-downloads/releases)

### ROSTAG PCP — controle do planejamento de projetos
Substitui uma planilha de controle de commessas. Cada projeto recebe o checklist padrão do PCP como cronograma encadeado, com datas calculadas a partir das durações, duas janelas de prazo, paralisação com contagem do tempo parado, notificações, painel de indicadores e linha do tempo. Visualização aberta por link; edição só com login, travada nas regras do Firestore.

`HTML/JS` `Firebase` `GitHub Pages` `Chart.js` · [Repositório](https://github.com/GuisBraz/rostag-pcp)

### CNC Gestão — programação de corte plasma e oxicorte
Fila de programas CNC por máquina, perfis por função (PCP, operador, gestão), cronômetro e alerta de atraso, agendamento que considera paradas planejadas e feriados, calendário mensal e Modo TV para o chão de fábrica.

`React` `Firebase` `Vercel` `Recharts`

### Carga Máquina Usinagem — *protótipo funcional*
Alternativa ao MS Project para programar mandrilhadoras, tornos, centros de usinagem e setores manuais. Lê as OPs do ERP, respeita a sequência do roteiro, bloqueia sobreposição de máquina e sinaliza prazos estourados. Validado com dados reais de 54 operações em 9 máquinas.

`HTML` `JavaScript` `Integração com ERP (Protheus)`

## Em desenvolvimento

### Simulador de empenamento na solda
Importar o modelo 3D da peça, marcar as soldas como na aba Welding do Inventor e estimar a distorção considerando aporte térmico, volume de solda, espessura e processo (GMAW, FCAW, TIG), além do tempo de solda.
**Etapa atual:** visualizador 3D que abre arquivos STEP direto no navegador.

`Three.js` `OpenCascade (WebAssembly)`

## Ferramentas

| Área | Ferramentas |
|---|---|
| Engenharia / CAD | Autodesk Inventor (análise de tensões), AutoCAD 2D/3D, Lantek |
| Gestão industrial | TOTVS Protheus, Excel / VBA |
| Desenvolvimento | Python, JavaScript, React, Firebase, Supabase, Vercel |

## Contato

Aberto a oportunidades em engenharia de processos, PCP e soluções digitais para a indústria.

- [LinkedIn](https://www.linkedin.com/in/guilherme-santos-66b8162a0)
- E-mail: [SEU E-MAIL]

---

<sub>Telas e exemplos usam dados fictícios. © 2026 Guilherme dos Santos Braz</sub>
