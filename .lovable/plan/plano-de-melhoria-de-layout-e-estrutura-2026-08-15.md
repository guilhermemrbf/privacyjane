# Plano de Melhoria de Layout e Estrutura

Vamos atualizar o layout da página `public/sales.html` para torná-la mais próxima da estrutura moderna das plataformas de conteúdo, baseando-se nas referências enviadas, sem alterar os textos ou fotos existentes.

## Alterações Visuais

1.  **Cabeçalho e Navegação Superior**
    *   Ajustar o alinhamento do logotipo e ícones de navegação (Chat, Notificações) para um estilo mais "limpo".
    *   Garantir que os contadores de mídias (Postagens, Mídias) fiquem em uma barra horizontal moderna com abas.

2.  **Seção de Perfil e Assinaturas**
    *   Refinar a área da foto de perfil e biografia para usar fontes e espaçamentos mais elegantes (Montserrat/Roboto).
    *   Estilizar os botões de assinatura para usarem bordas arredondadas suaves e gradientes que acompanhem a identidade visual das imagens de referência.
    *   Adicionar uma seção de "Promoções" agrupada, conforme visto na captura de tela.

3.  **Grade de Conteúdo (Feed)**
    *   Implementar a grade de miniaturas com os contadores de curtidas e mídias sobrepostos na parte inferior de cada card.
    *   Adicionar os ícones de cadeado e badges de categoria (FOTO/VÍDEO) com um design mais minimalista e fiel às referências.

## Detalhes Técnicos

*   **HTML/CSS:** As alterações serão feitas diretamente no arquivo `public/sales.html`, utilizando classes CSS existentes e adicionando estilos inline ou em blocos `<style>` para garantir a compatibilidade.
*   **Responsividade:** O foco será manter a fluidez tanto em dispositivos móveis quanto desktop, ajustando as colunas da grade (ex: 3 colunas no mobile).
*   **Fontes:** Utilização consistente das fontes Montserrat e Roboto já importadas no projeto.
*   **Ícones:** Uso de FontAwesome para ícones de cadeado, fotos e vídeos.

---
**Nota:** Não modificaremos o conteúdo dos textos (Jane, @janevódohot, descrição, preços) nem as fotos de capa/perfil já configuradas.
