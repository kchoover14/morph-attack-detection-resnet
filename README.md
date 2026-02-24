## Morph Attack Detection Using ResNet50 and Transfer Learning

Morphing attacks blend two faces into a single image to create identity documents that pass automated face recognition for both individuals. This project trains a binary classifier on the Labeled Faces in the Wild dataset -- 250 genuine and 250 alpha-blended morphed images -- using a fine-tuned ResNet50 with transfer learning. The classifier achieved 93% test accuracy, 98% precision, and 89% recall on morphed images, correctly identifying all genuine faces while missing 11% of morphs. Grad-CAM analysis confirmed the model attends to blending artifacts at face edges and texture boundaries, and identified three systematic failure modes: blur, angled faces, and heavy facial hair.

## Portfolio Page

The [portfolio page](https://kchoover14.github.io/morph-attack-detection-resnet) includes a full project narrative, key findings, and figures.

## Tools & Technologies

**Languages:** Python

**Tools:** PyTorch

**Packages:** numpy | pandas | matplotlib | seaborn | Pillow | opencv-python | tqdm | torch | torchvision | scikit-learn

## Expertise

Demonstrates ability to design and evaluate a deep learning pipeline from data generation through deployment recommendation, using explainability tools to translate model behavior into operationally actionable quality standards and threshold guidance.

## License

- Code and scripts are licensed under the [MIT License](LICENSE).
- Data, figures, and written content © Kara C. Hoover, licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).
