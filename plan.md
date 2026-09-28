# Plano — Barbearia Dom Ribeiro

## Resultado
Landing page pública, estática e mobile-first para a Barbearia Dom Ribeiro, com identidade de selo vintage urbano, foco em conversão direta para WhatsApp e conteúdo visível no HTML inicial.

## Arquitetura
- **Frontend:** um único `index.html` com HTML semântico, CSS embutido e JavaScript puro.
- **Assets:** `domribeirologo.jpg` como logo/fav icon; nenhum ambiente/corte artificial será inventado.
- **Interações:** menu mobile, rolagem suave, botões de WhatsApp com mensagem pré-preenchida, ano 2026 e entrada sutil das seções.
- **Dados editáveis:** serviços, preços, telefone, endereço, horários e textos principais terão comentários claros no código.

## Direção visual
Fundo preto dominante, dourado envelhecido para hierarquia e detalhes, branco para leitura; tipografia serifada forte para marca e sans-serif para corpo; ornamentos finos inspirados em emblemas circulares de barbearia, sem aparência old-school excessiva.

## Servir e publicar
Como todo o conteúdo pode ser entregue pronto para visita e a stack obrigatória é HTML/CSS/JS sem build tool, a opção adequada é publicação estática. Não há servidor, banco, login, API própria ou rotas dinâmicas. A raiz contém `index.html`; os assets ficam no mesmo diretório para compatibilidade com GitHub Pages. O HTML permanece sem cache agressivo; a logo é um asset público pequeno.

## SEO e acessibilidade
Conteúdo real estará no HTML inicial, com título, description, Open Graph sem URL absoluta inventada, headings semânticos, `alt` na logo, `aria-label` nos controles e foco visível. Não será criado canonical/sitemap com endereço desconhecido; isso pode ser acrescentado quando o domínio público for definido.

## Verificação
- Inspeção do código para conferir todos os dados do briefing e ausência de frameworks.
- Verificação sintática básica e teste HTTP da prévia.
- Diagnósticos do workspace Webdev quando aplicável.
- Revisão independente read-only da conexão entre seções e links críticos antes da entrega.
