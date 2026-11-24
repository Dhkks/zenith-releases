# zenith — Releases

Instaladores públicos do **zenith**, um workspace desktop para orquestrar agentes de IA de código (Claude, Codex, Gemini e outros) em grids de terminais.

## Download

O instalador mais recente está na [página de Releases](https://github.com/Dhkks/zenith-releases/releases/latest).

| Plataforma | Arquitetura | Arquivo |
|------------|-------------|---------|
| Windows 10/11 | x64 | `zenith_X.Y.Z_x64-setup.exe` |
| macOS (Apple Silicon: M1 ou mais novo) | arm64 | `zenith_X.Y.Z_aarch64.dmg` |

## Instalação (Windows)

O instalador ainda **não tem assinatura de código** (sem certificado Authenticode). Na primeira vez:

1. Baixe o `zenith_X.Y.Z_x64-setup.exe` da última release.
2. Abra o arquivo. Se o SmartScreen avisar, clique em **Mais informações** → **Executar assim mesmo**.
3. O instalador roda sozinho e abre o zenith no fim.

## Instalação (macOS)

O app ainda **não tem assinatura da Apple** (sem Developer ID). Na primeira vez:

1. Baixe o `zenith_X.Y.Z_aarch64.dmg` da última release.
2. Abra o `.dmg` e arraste o **zenith** para a pasta **Aplicativos**.
3. Em **Aplicativos**, clique com o botão direito no zenith → **Abrir** → **Abrir**.
4. Se o macOS disser que o app está "danificado", rode no Terminal e abra de novo:

   ```bash
   xattr -cr /Applications/zenith.app
   ```

Macs com processador Intel não são suportados.

## Atualização automática

Ao abrir, o zenith verifica se há versão nova. Quando há, ele pergunta se pode instalar; ao aceitar, o app fecha, atualiza e reabre. As atualizações são assinadas e verificadas pelo app antes de instalar.

Arquivos de cada release:

- `zenith_X.Y.Z_x64-setup.exe` — instalador do Windows.
- `zenith_X.Y.Z_x64-setup.exe.sig` — assinatura da atualização do Windows.
- `zenith_X.Y.Z_aarch64.dmg` — instalador do macOS.
- `zenith_X.Y.Z_aarch64.app.tar.gz` — atualização do macOS.
- `zenith_X.Y.Z_aarch64.app.tar.gz.sig` — assinatura da atualização do macOS.
- `latest.json` — manifesto que o app lê para achar a versão nova.

## Código-fonte

O código-fonte é fechado e fica em um repositório privado. Este repositório tem só os binários.
