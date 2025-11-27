# ExifTool
---
O objetivo desta atividade é estudar e entender como arquivos (especificamente imagens) podem carregar informações ocultas (metadados) e como ferramentas de linha de comando podem ser usadas para proteger a privacidade e evitar a exposição desnecessária de dados.

---
## Ferramentas

* ExifTool  
* Kali Linux

---

## Instalando o ExifTool
ExifTool é uma ferramenta multiplataforma. A instalação varia dependendo do sistema operacional:

```
sudo apt update
sudo apt install libimage-exiftool-perl
```

---

## Passos Práticos Realizados

```
exiftool image.jpeg
```

```
exiftool -all= image.jpeg
```

```
exiftool image.jpeg
```

**Resultado Esperado:**  
A saída agora deve mostrar apenas informações mínimas e essenciais do formato JPEG, sem os dados sensíveis (como nome da câmera, autor ou coordenadas GPS) que estavam presentes no primeiro passo. Essa confirmação garante que a limpeza foi realizada com sucesso.
