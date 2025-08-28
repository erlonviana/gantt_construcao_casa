# gantt_construcao_casa

```mermaid
gantt
  title Gantt Construção da Casa
  dateFormat YYYY-MM-DD

  section Planejamento e aprovações
  Preparo desenhos arquitetônicos :active, a1, 2025-02-02, 6d
  Aprovação dos documentos :done, a2, after a1, 7d
  Criação do plano de construção :crit, a3, after a2, 7d 

  section Preparação do terreno
  Limpeza :done, a4, after a3, 5d
  Nivelamento :crit, a5, after a4, 5d

  section Fundação da casa
  Escavação :active, a6, after a5, 5d
  Fundações de concreto :done, a7, after a6, 5d
  Impermeabilização :done, a8, after a7, 5d

  section Estruturação da casa
  Paredes :future, a9, after a8, 9d
  Colunas :future, a10, after a9, 7d
  Vigas :future, a11, after a10, 7d
  Telhado :future, a12, after a11, 7d

  section Instalações elétricas e hidráulicas
  Tubulações de agua e esgoto :future, a13, after a12, 7d
  Fiação :future, a14, after a13, 7d
  Painéis elétricos :future, a15, after a14, 6d

  section Acabamento interno
  Reboco :future, a16, after a15, 6d
  Pintura :future, a17, after a16, 6d
  Instalação de portas e janelas :future, a18, after a17, 6d
  Detalhes de acabamento :future, a19, after a18, 7d

  section Acabamento externo
  Pintura :future, a20, after a19, 5d
  Paisagismo :future, a21, after a20, 5d
  Instalação de cercas :future, a22, after a21, 5d

  section Inspeção final
  Inspeção e entrega da casa :milestone, a23, after a22


```
