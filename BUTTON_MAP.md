# Mapa de Botões - Hazak Fit Website

Este documento contém o mapeamento de todos os botões e elementos clicáveis do site Hazak Fit, organizados por seção com seus respectivos IDs para rastreamento e analytics.

## Estrutura de IDs

Todos os IDs seguem o padrão: `[seção]-[ação]-[elemento]-[tipo]`

- **seção**: Área do site onde o botão está localizado
- **ação**: Ação principal do botão (ex: nav, cta, toggle)
- **elemento**: Elemento específico (opcional)
- **tipo**: Sufixo que indica o tipo de botão:
  - `btn`: Botões padrão (navegação, toggle, etc.)
  - `wpp-btn`: Botões que direcionam para WhatsApp

## Seção: Header (Cabeçalho)

| ID | Elemento | Descrição | Ação |
|---|---|---|---|
| `header-logo-btn` | Logo HAZAK fit | Link principal do logo | Navega para o topo |
| `header-nav-home-btn` | Menu "Início" | Link de navegação | Navega para #home |
| `header-nav-about-btn` | Menu "Sobre" | Link de navegação | Navega para #about |
| `header-nav-structure-btn` | Menu "Estrutura" | Link de navegação | Navega para #structure |
| `header-nav-plans-btn` | Menu "Planos" | Link de navegação | Navega para #plans |
| `header-assine-agora-wpp-btn` | Botão "Fazer Matrícula" | CTA principal | WhatsApp |
| `mobile-menu-toggle` | Menu hambúrguer | Toggle menu mobile | Abre/fecha menu |
| `mobile-nav-home-btn` | Mobile "Início" | Link navegação mobile | Navega para #home |
| `mobile-nav-about-btn` | Mobile "Sobre" | Link navegação mobile | Navega para #about |
| `mobile-nav-structure-btn` | Mobile "Estrutura" | Link navegação mobile | Navega para #structure |
| `mobile-nav-plans-btn` | Mobile "Planos" | Link navegação mobile | Navega para #plans |
| `mobile-assine-agora-wpp-btn` | Mobile "Fazer Matrícula" | CTA mobile | WhatsApp |

## Seção: Hero (Banner Principal)

| ID | Elemento | Descrição | Ação |
|---|---|---|---|
| `hero-fazer-matricula-wpp-btn` | Botão "Fazer Matrícula" | CTA principal | WhatsApp |
| `hero-conhecer-planos-btn` | Botão "Fazer Matrícula" | CTA secundário | Navega para #plans |

## Seção: About (Sobre)

| ID | Elemento | Descrição | Ação |
|---|---|---|---|
| `about-matricule-se-agora-wpp-btn` | Botão "Fazer Matrícula" | CTA da seção | WhatsApp |

## Seção: Plans (Planos e Preços)

### Botões de Planos Principais
| ID | Elemento | Descrição | Ação |
|---|---|---|---|
| `plan-monthly-btn` | Toggle "Mensal" | Seleção de plano | Ativa plano mensal |
| `plan-quarterly-btn` | Toggle "Trimestral" | Seleção de plano | Ativa plano trimestral |
| `plan-semiannual-btn` | Toggle "Semestral" | Seleção de plano | Ativa plano semestral |
| `plan-annual-btn` | Toggle "Anual" | Seleção de plano | Ativa plano anual |

### CTAs de Planos
| ID | Elemento | Descrição | Ação |
|---|---|---|---|
| `plan-monthly-cta-wpp-btn` | "Fazer Matrícula" Mensal | CTA plano mensal | WhatsApp |
| `plan-quarterly-cta-wpp-btn` | "Fazer Matrícula" Trimestral | CTA plano trimestral | WhatsApp |
| `plan-semiannual-cta-wpp-btn` | "Fazer Matrícula" Semestral | CTA plano semestral | WhatsApp |
| `plan-annual-cta-wpp-btn` | "Fazer Matrícula" Anual | CTA plano anual | WhatsApp |

### Outros Planos
| ID | Elemento | Descrição | Ação |
|---|---|---|---|
| `outros-planos-amigos-wpp-btn` | Plano AMIGOS | Card de plano | WhatsApp |
| `outros-planos-estudantil-wpp-btn` | Plano ESTUDANTIL | Card de plano | WhatsApp |
| `outros-planos-3x-wpp-btn` | Plano 3X | Card de plano | WhatsApp |
| `outros-planos-4x-wpp-btn` | Plano 4X | Card de plano | WhatsApp |
| `plans-contact-wpp-btn` | "Fazer Matrícula" | CTA de contato | WhatsApp |

## Seção: Gallery (Galeria)

| ID | Elemento | Descrição | Ação |
|---|---|---|---|
| `gallery-prev-btn` | Setra anterior | Navegação | Imagem anterior |
| `gallery-next-btn` | Setra próxima | Navegação | Próxima imagem |
| `gallery-dot-0-btn` | Dot 1 | Navegação | Imagem 1 |
| `gallery-dot-1-btn` | Dot 2 | Navegação | Imagem 2 |
| `gallery-dot-2-btn` | Dot 3 | Navegação | Imagem 3 |
| `gallery-dot-3-btn` | Dot 4 | Navegação | Imagem 4 |
| `gallery-dot-4-btn` | Dot 5 | Navegação | Imagem 5 |
| `gallery-dot-5-btn` | Dot 6 | Navegação | Imagem 6 |
| `gallery-dot-6-btn` | Dot 7 | Navegação | Imagem 7 |
| `gallery-dot-7-btn` | Dot 8 | Navegação | Imagem 8 |

## Seção: Team (Equipe)

| ID | Elemento | Descrição | Ação |
|---|---|---|---|
| `team-prev-btn` | Setra anterior | Navegação | Membro anterior |
| `team-next-btn` | Setra próxima | Navegação | Próximo membro |

## Seção: Toast (Notificações)

| ID | Elemento | Descrição | Ação |
|---|---|---|---|
| `toast-close-btn` | Botão fechar | Fechar notificação | Fecha toast |

## Seção: Footer (Rodapé)

| ID | Elemento | Descrição | Ação |
|---|---|---|---|
| `footer-dev-link-btn` | Link desenvolvedor | Link externo | Abre dani.dev.br |
| `footer-instagram-btn` | Ícone Instagram | Rede social | Instagram |
| `footer-facebook-btn` | Ícone Facebook | Rede social | Facebook |

## Eventos de Rastreamento Sugeridos

### Google Tag Manager Events
- **page_view**: Visualização de página
- **click_header_cta**: Cliques em CTAs do header
- **click_hero_cta**: Cliques em CTAs do hero
- **click_about_cta**: Cliques em CTAs da seção sobre
- **click_plan_selection**: Seleção de planos
- **click_plan_cta**: Cliques em CTAs de planos
- **gallery_navigation**: Navegação na galeria
- **team_navigation**: Navegação na equipe
- **social_media_click**: Cliques em redes sociais
- **contact_whatsapp**: Todos os cliques para WhatsApp

### Parâmetros Sugeridos
- **button_id**: ID do botão clicado
- **section**: Seção onde o botão está
- **action**: Tipo de ação (navigation, cta, social)
- **destination**: Destino do link (whatsapp, internal, external)

## Implementação

```javascript
// Exemplo de implementação GTM
document.addEventListener('click', function(e) {
    const button = e.target.closest('button, a[href]');
    if (button && button.id) {
        window.dataLayer = window.dataLayer || [];
        window.dataLayer.push({
            event: 'button_click',
            button_id: button.id,
            section: button.id.split('-')[0],
            action: getActionFromId(button.id),
            destination: getDestinationFromElement(button)
        });
    }
});
```

## Notas

- Todos os botões de WhatsApp utilizam o mesmo número: (77) 99862-0419
- Links internos usam âncoras (#section)
- Links externos abrem em nova aba (target="_blank")
- Botões de navegação mobile fecham o menu após clique
- IDs são únicos e seguam padrão consistente para fácil manutenção
