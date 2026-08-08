# Writeups de segurança

> ⚠ **Em construção** — a documentação está pronta; o código está em migração e será publicado em breve.

Análises técnicas de vulnerabilidades que encontrei e reportei. Publico apenas o que já foi corrigido e divulgado pelo programa responsável.

## Achados

| Data | Alvo | Falha | Severidade | Situação |
|---|---|---|---|---|
| «2026-04» | google-cloud-cpp | Heap-buffer-overflow | P2/S2 | corrigida |
| «2026-05» | Google API | Path Traversal + Field Mask Injection | P2/S2 | corrigida |
| «2026-06» | Razer | Information Disclosure / LFI | — | reportada |

## Formato

Cada writeup segue a mesma estrutura: o que o sistema deveria fazer, o que ele fazia, como cheguei lá, qual o impacto real e como foi corrigido. Sem detalhe operacional que sirva para atacar instalações ainda não atualizadas.

## Divulgação responsável

Nada é publicado antes da correção estar disponível e o programa autorizar. Achados em validação ficam fora deste repositório até lá.
