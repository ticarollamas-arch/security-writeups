<p align="center"><img src="assets/banner.svg" alt="Writeups de Segurança — análises de vulnerabilidades reportadas e corrigidas" width="100%"></p>

# Writeups de segurança — vulnerabilidades reportadas em bug bounty

Análises técnicas de vulnerabilidades que encontrei e reportei em programas de **bug bounty**. Só publico o que já foi **corrigido e autorizado** pelo programa responsável, seguindo a **divulgação responsável**.

> **Em construção**: o modelo de writeup está pronto; os textos completos serão publicados à medida que as correções e as autorizações de divulgação saírem.

## Achados

| Data | Alvo | Falha | Severidade | Situação |
|---|---|---|---|---|
| 2026-04 | google-cloud-cpp | Heap buffer overflow | P2/S2 | Corrigida |
| 2026-05 | Google API | Path traversal + field mask injection | P2/S2 | Corrigida |
| 2026-06 | Razer | Information disclosure / LFI | — | Reportada |

## Formato dos writeups

Cada writeup segue a mesma estrutura, definida em [template-writeup.md](template-writeup.md):

- **Cabeçalho**: programa, severidade, CWE, datas do report e da correção.
- **Resumo**: componente, falha e impacto em poucas frases.
- **Contexto**: o que o sistema deveria fazer.
- **Comportamento observado** e **como cheguei lá**.
- **Impacto real** e **correção** aplicada.

Os textos não incluem detalhes operacionais que permitam atacar instalações ainda não atualizadas.

## Como usar

Leia os writeups publicados neste repositório ou use o modelo para documentar seus próprios achados:

```bash
git clone https://github.com/ticarollamas-arch/security-writeups.git
cp security-writeups/template-writeup.md meu-writeup.md
```

## Divulgação responsável

Nada é publicado antes de a correção estar disponível e de o programa autorizar. Achados ainda em validação ficam fora deste repositório.

## Licença

Distribuído sob a licença MIT. Veja [LICENSE](LICENSE).
