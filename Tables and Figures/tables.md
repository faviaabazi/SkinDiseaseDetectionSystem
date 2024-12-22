# Table 1 - Model Performance Metrics

| Model        | Best Train Loss | Best Train Accuracy | Best Validation Loss | Best Val. Accuracy | Test Loss | Test Accuracy |
|--------------|-----------------|---------------------|----------------------|--------------------|-----------|---------------|
| ResNet       | 0.7749          | 77.21%              | 0.6522               | 78.38%             | 0.6522    | 78.38%        |
| DenseNet     | 0.7012          | 79.77%              | 0.5843               | 82.43%             | 0.5843    | 82.43%        |
| EfficientNet | 2.1883          | 52.71%              | 1.8451               | 59.46%             | 1.8451    | 59.46%        |
| AlexNet      | 0.7003          | 72.93%              | 0.6045               | 77.03%             | 0.6045    | 77.03%        |

# Table 2 - Batch Size Performance Metrics

| Batch Size | Train Accuracy | Validation Accuracy| Train Loss | Validation Loss | Best Val. Accuracy |
|------------|----------------|--------------------|------------|-----------------|--------------------|
| 16         | 0.4900         | 0.5150             | 1.8706     | 1.9347          | 51.50%             |
| 32         | 0.4424         | 0.4425             | 2.0889     | 2.1591          | 44.25%             |
| 64         | 0.3386         | 0.3663             | 2.5527     | 2.4756          | 36.63%             |
