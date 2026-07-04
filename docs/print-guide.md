# Print Guide

## File

Use:

```text
models/victory-swallow-2_20cm_4color_v1.1.0.3mf
```

The 3MF file is a Bambu Studio project with multiple plates and filament assignments.

## Latest Version

`v1.1.0` fixes a blocking printability issue in the previous `v1.0.0` release. Use `v1.1.0` or newer for printing.

`v1.1.0` 修复了旧版 `v1.0.0` 中会导致无法顺利打印的问题。请使用 `v1.1.0` 或更新版本进行打印。

## Confirmed Profile

| Item | Setting |
| --- | --- |
| Slicer | Bambu Studio 02.07.01.62 |
| Printer profile | Bambu Lab A1 |
| Plate | Textured PEI Plate |
| Nozzle in included profile | 0.4 mm |
| Recommended nozzle at original scale | 0.2 mm |
| Recommended scale for 0.4 mm nozzle | 120% or larger |
| Layer height | 0.12 mm |
| First layer height | 0.2 mm |
| Material | Bambu Lab PLA |
| Infill | 20% |
| Supports | Tree auto |
| Brim | Auto brim |
| Walls | 2 |
| Top shell layers | 5 |
| Bottom shell layers | 5 |

## Filament Mapping

| Slot | Color | Hex | Material |
| --- | --- | --- | --- |
| 1 | Yellow | `#F4EE2A` | PLA |
| 2 | Black | `#000000` | PLA |
| 3 | Red | `#C12E1F` | PLA |
| 4 | White | `#FFFFFF` | PLA |

Before printing, check that your AMS or filament assignment matches these colors.

## Nozzle and Scale Recommendation

At the original scale, this model contains small details and thin color-separated features. The author was able to print and assemble it with a 0.4 mm nozzle, but the detail precision is only fair and glue was used for assembly.

For the original-scale file, a 0.2 mm nozzle is recommended. If you use a 0.4 mm nozzle, scale the model to at least 120% before printing.

原始比例下，本模型包含较多小细节和较薄的彩色分件特征。作者尝试使用 0.4 mm 打印头完成了打印和组装，但细节精度一般，并且组装时使用了胶水。

原始比例建议使用 0.2 mm 打印头。如果使用 0.4 mm 打印头，建议至少放大到 120% 以上再打印。

## Recommended Workflow

1. Open the 3MF in Bambu Studio.
2. Confirm the printer, plate type, filament slots, and object colors.
3. Inspect every plate before slicing.
4. Re-slice on your own machine profile.
5. Print one small/detail plate first if you are unsure about fit, support removal, or color mapping.
6. Dry-fit parts before gluing.

## Notes

- The model is prepared for a target width of about 20 cm at the included scale.
- The included setup was made for PLA on a textured PEI plate.
- If you use another printer, nozzle, filament, or slicer, inspect supports and tolerances carefully.
- Small details may need slower speeds, clean supports, and careful cooling.
- The model is provided as-is; print results may vary.
