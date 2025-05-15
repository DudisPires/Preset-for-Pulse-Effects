# Preset-for-Pulse-Effects

# 💻 O que é o Pulse Effects?

```
O PulseEffects é um software de processamento de áudio para Linux
que permite aplicar efeitos em tempo real no som de entrada e/ou saída do sistema.

```

Foco do Preset:
      
      - Amplificar o grave sem efeitos prejudiciais em outras frequências.
      - Melhorar a experiência ao ouvir musicas com o apoio de um equalizador externo.
      - Regular o grave desbalanceado da maioria dos programas do cotidiano. 

---

## 🚀 Como rodar o projeto

1. Instalar Pulse Effects ( com Pulse Audio )

```bash
   ' sudo apt install pulseeffects '
```
2. Inserir o arquivo `.json` em `PulseEffects/output`

   Utilize o comando a seguir ou insira manualmente.

   ```
   curl -o Preset-bass.json "https://raw.githubusercontent.com/DudisPires/Preset-for-Pulse-Effects/refs/heads/main/Preset-bass.json?token=GHSAT0AAAAAADD2W4XSJ6VG4WCTILPBCGAU2BGOSTA"
   mv Preset-bass.json ~/.config/PulseEffects/output/

   ```

4. Selecionar no Pulse Effects o `Preset-bass`
   

