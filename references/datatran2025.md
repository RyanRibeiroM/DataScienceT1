# Acidentes de Trânsito (datatran2025)

**Resumo do Conjunto de Dados:**

- **Total de Amostras (Linhas):** 47192
- **Total de Atributos (Colunas):** 30

---

### Tabela de Atributos

| Nome                       | Tipo               | Descrição                                                  | Unidades | Valores Faltantes |
| :------------------------- | :----------------- | :--------------------------------------------------------- | :------- | :---------------- |
| **id**                     | Numérico (Inteiro) | Identificador único para cada registro de acidente.        | N/A      | 0                 |
| **data_inversa**           | Data/Hora          | Data em que a ocorrência do acidente foi registrada.       | N/A      | 0                 |
| **dia_semana**             | Ordinal            | Dia da semana em que o acidente ocorreu.                   | N/A      | 0                 |
| **horario**                | Data/Hora          | Hora aproximada do acidente.                               | Horas    | 0                 |
| **uf**                     | Categórico         | Sigla da Unidade Federativa (Estado) do acidente.          | N/A      | 0                 |
| **br**                     | Numérico (Inteiro) | Número da rodovia federal (BR) onde ocorreu.               | N/A      | 0                 |
| **km**                     | Numérico (Float)   | Marco quilométrico da rodovia onde ocorreu.                | Km       | 0                 |
| **municipio**              | Categórico         | Nome do município onde o acidente foi registrado.          | N/A      | 0                 |
| **causa_acidente**         | Textual            | Descrição da causa principal do acidente.                  | N/A      | 0                 |
| **tipo_acidente**          | Categórico         | Classificação do tipo de acidente (ex: colisão).           | N/A      | 0                 |
| **classificacao_acidente** | Ordinal            | Gravidade do acidente (ex: Com Vítimas, Sem Vítimas).      | N/A      | 1                 |
| **fase_dia**               | Ordinal            | Período do dia (ex: Pleno dia, Plena noite).               | N/A      | 0                 |
| **sentido_via**            | Categórico         | Sentido da via (Crescente ou Decrescente).                 | N/A      | 0                 |
| **condicao_metereologica** | Categórico         | Condições do tempo no momento do acidente.                 | N/A      | 0                 |
| **tipo_pista**             | Categórico         | Tipo de pista da rodovia (Simples, Dupla, Múltipla).       | N/A      | 0                 |
| **tracado_via**            | Categórico         | Geometria da via no local do acidente (Reta, Curva, etc.). | N/A      | 0                 |
