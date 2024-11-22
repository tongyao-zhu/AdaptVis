# AdaptVis: Spatial Understanding in Vision-Language Models Requires Adaptive Attention


## Running experiments scaling_vis and adapt_vis
You can fast implement an example by:
```
bash run.sh
```
### Argument
| Argument       | Example               | Description                                                                                   |
|----------------|-----------------------|-----------------------------------------------------------------------------------------------|
| `dataset`          | `Controlled_Images_A` | Specifies the dataset you want to evaluate. Can choose from `Controlled_Images_A, Controlled_Images_B..`. |
| `model`              | `llava1.5`            | Specifies the model you want to use.                                                          |
| `method`                | `scaling_vis`         | The method for evaluation. Can choose from `"scaling_vis"` or `"adapt_vis"`.                  |
| `weight`                   | `1.2`                 | Coefficient for Scaling_vis. Can set from `[0, 5, 0.8, 1.2, 1.5, 2.0]`.                       |
| `weight1`           | `0.5`                 | Coefficient for AdaptVis. Can set from `[0.5, 0.8]`.                                          |
| `weight2`          | `1.2`                 | Coefficient for AdaptVis. Can set from `[1.2, 1.5, 2.0]`.                                     |
| `th`                 | `0.3`                 | Threshold for AdaptVis.                                                                        |

