| Tabela 2. Módulos da plataforma e tecnologias |                                                   |                                    |
|-----------------------------------------------|---------------------------------------------------|------------------------------------|
|                                               |                                                   |                                    |
| Módulo                                        | Funcionalidade                                    | Tecnologia Principal               |
| Captura                                       | Upload, pré-processamento e validação do formato  | HTML5, JavaScript, OpenCV (Python) |
| Detecção                                      | Localização da folha A4 e segmentação precisa     | YOLOv8s, SAM2, OpenCV              |
| Reconhecimento de Regiões                     | Detecção de answer_area_enem e day_region         | YOLOv11s, OpenCV                   |
| OCR/OMR                                       | Leitura do dia da prova e extração das marcações  | Tesseract, OpenCV                  |
| Correção Automática                           | Comparação com os gabaritos de referência         | Python, Pandas, NumPy              |
| Gestão                                        | Armazenamento, relatórios e visualização de dados | Node.js, SQLite, Chart.js          |
| Interface Web                                 | Frontend responsivo para upload e resultados      | HTML5, CSS3, JavaScript            |
