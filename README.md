# Zenith — Releases

Instaladores públicos do **Zenith**, um workspace desktop para orquestrar agentes de IA de código (Claude, Codex, Gemini e outros) em grids de terminais.

## Download

O instalador mais recente está na [página de Releases](https://github.com/Dhkks/zenith-releases/releases/latest).

| Plataforma | Arquitetura | Arquivo |
|------------|-------------|---------|
| Windows 10/11 | x64 | `Zenith_X.Y.Z_x64-setup.exe` |

## Instalação (Windows)

O instalador ainda **não tem assinatura de código** (sem certificado Authenticode). Na primeira vez:

1. Baixe o `Zenith_X.Y.Z_x64-setup.exe` da última release.
2. Abra o arquivo. Se o SmartScreen avisar, clique em **Mais informações** → **Executar assim mesmo**.
3. O instalador roda sozinho e abre o Zenith no fim.

## Atualização automática

Ao abrir, o Zenith verifica se há versão nova. Quando há, ele pergunta se pode instalar; ao aceitar, o app fecha, atualiza e reabre. As atualizações são assinadas e verificadas pelo app antes de instalar.

Arquivos de cada release:

- `Zenith_X.Y.Z_x64-setup.exe` — instalador.
- `Zenith_X.Y.Z_x64-setup.exe.sig` — assinatura da atualização.
- `latest.json` — manifesto que o app lê para achar a versão nova.

## Código-fonte

O código-fonte é fechado e fica em um repositório privado. Este repositório tem só os binários.
