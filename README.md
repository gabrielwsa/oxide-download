<p align="center">
  <img src="icon.png" width="96" alt="Oxide">
</p>

<h1 align="center">Oxide</h1>

<p align="center">
  Cliente de APIs para desktop: requisições, coleções, scripts, Flows, mock servers e Catálogo de APIs.<br>
  <sub>Antes chamado RequestPost.</sub>
</p>

<p align="center">
  <a href="../../releases/latest"><b>⬇ Baixar a versão mais recente</b></a>
</p>

---

## Instalação

Abra a [página de releases](../../releases/latest) e baixe o arquivo do seu sistema:

| Sistema | Arquivo | Como instalar |
|---|---|---|
| **Windows** | `Oxide-Setup-x.y.z.exe` | Execute o instalador. Se aparecer "O Windows protegeu o computador", clique em **Mais informações → Executar assim mesmo**. |
| **Arch Linux** | `Oxide-x.y.z-x86_64.pkg.tar.xz` | `sudo pacman -U Oxide-*.pkg.tar.xz` (aparece no menu de aplicativos; remova com `sudo pacman -R Oxide`). Substitui o pacote antigo `RequestPost`. |
| **Linux** (qualquer distro) | `Oxide-x.y.z.AppImage` | `chmod +x Oxide-*.AppImage` e execute. Na primeira vez ele cria o atalho no menu de aplicativos. |
| **macOS** (Apple Silicon) | `Oxide-x.y.z-arm64.dmg` | Arraste para Aplicativos. Na primeira vez, clique com o botão direito no app → **Abrir**. Nem toda versão tem instalador para macOS: use o da versão mais recente que tiver. |

Os instaladores ainda não têm assinatura digital, por isso o Windows e o macOS pedem confirmação na primeira execução.

### Atualizações

A partir da versão 0.1.9 o app procura versões novas sozinho (ao abrir e a cada 4 horas) e mostra um aviso no topo:

- **Windows** e **AppImage**: clique em **Atualizar**; a nova versão é baixada em segundo plano e instalada ao clicar em **Reiniciar e atualizar** (ou ao fechar o app).
- **macOS** e **Arch Linux**: o aviso abre esta página para baixar a nova versão.

Também dá para verificar em **Configurações → Atualizações → Verificar agora**.

Os seus dados (coleções, ambientes, flows) ficam no seu computador. Quem usava o RequestPost não perde nada: na primeira vez que o Oxide abre, ele copia os dados da versão anterior.
