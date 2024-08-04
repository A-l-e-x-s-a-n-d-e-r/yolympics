# YOLOv8 Detecção de Movimentos

Este repositório contém código para detectar e classificar movimentos usando o modelo de detecção de objetos YOLOv8. O projeto utiliza técnicas de visão computacional para processar frames de vídeo, identificar pontos-chave e classificar vários movimentos.

## Recursos

- **Integração com YOLOv8**: Utiliza o modelo YOLOv8 para detecção de objetos precisa e eficiente.
- **Processamento de Vídeo**: Processa os primeiros 10% de um vídeo de entrada para detectar pontos-chave e movimentos.
- **Classificação de Movimentos**: Classifica movimentos em categorias com base nos pontos-chave detectados e suas posições.
- **Visualização em Tempo Real**: Exibe informações em tempo real no vídeo processado, incluindo contagem de saltos, giros e passos.
- **Pontos-chave Personalizáveis**: Permite fácil ajuste dos IDs dos pontos-chave para diferentes casos de uso.

## Começando

1. **Instale as Dependências**: Certifique-se de ter as bibliotecas necessárias instaladas executando `pip install -r requirements.txt`.
2. **Prepare o Modelo**: Baixe e coloque o modelo YOLOv8 (`yolov8n-pose.pt`) no diretório apropriado.
3. **Execute o Código**: Execute o script para processar o vídeo e gerar a saída com os movimentos detectados.

## Autor

Este código foi desenvolvido por Alex Noves (alexnovaes@gmail.com). Permissão é concedida para copiar e evoluir o código, desde que a devida citação seja dada ao autor original.

## Licença

Este projeto é licenciado sob a Licença Apache 2.0. Veja o arquivo LICENSE para mais detalhes.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para enviar issues e pull requests para melhorar a funcionalidade e o desempenho deste projeto.

---

# YOLOv8 Movement Detection

This repository contains code for detecting and classifying movements using the YOLOv8 object detection model. The project leverages computer vision techniques to process video frames, identify keypoints, and classify various movements.

## Features

- **YOLOv8 Integration**: Utilizes the YOLOv8 model for accurate and efficient object detection.
- **Video Processing**: Processes the first 10% of an input video to detect keypoints and movements.
- **Movement Classification**: Classifies movements into categories based on detected keypoints and their positions.
- **Real-time Visualization**: Displays real-time information on the processed video, including counts of jumps, spins, and steps.
- **Customizable Keypoints**: Allows for easy adjustment of keypoint IDs to suit different use cases.

## Getting Started

1. **Install Dependencies**: Ensure you have the necessary libraries installed by running `pip install -r requirements.txt`.
2. **Prepare the Model**: Download and place the YOLOv8 model (`yolov8n-pose.pt`) in the appropriate directory.
3. **Run the Code**: Execute the script to process the video and generate the output with detected movements.

## Author

This code was developed by Alex Novaes (alexnovaes@gmail.com). Permission is granted for copying and evolving the code, provided that proper citation is given to the original author.

## License

This project is licensed under the Apache 2.0 License. See the LICENSE file for more details.

## Contributions

Contributions are welcome! Feel free to submit issues and pull requests to enhance the functionality and performance of this project.
