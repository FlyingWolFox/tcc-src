# tcc-src
Modificações e Código Fonte do TCC

## Instruções

1. Extraia o arquivo tcc-src.tar.zst. Está comprimitdo com Zstandard (zstd).
2. Crie o ambiente conda que nem

   ```bash
   conda create -n skimo_venv python=3.9
   conda activate skimo_venv
   ```

3. rode tcc-src-2-repo/skimo/install.sh: `sh install.sh`
4. instale stable-retro: `pip install stable-retro`
5. instale o retrowrapper: `pip install -e retrowrapper`
6. Substitua os arquivos de biblioteca instalados pelos que estão em arquivos_modificados
   - os caminhos dos arquivos está no arquivo arquivos_modificados.txt
   - mova cada arquivo dentro da pasta arquivos modificados pelo local apontado por arquivos_modificados.txt
7. Siga as instruções de como rodar do skimo. O arquivo de configuração é skimo_retro.yaml
