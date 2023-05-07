# Projeto Final - Modelos Preditivos Conexionistas

### Amanda Marcelle


|Classificação de Imagens | YOLOv5 | PyTorch |

## Performance

O modelo treinado possui performance de **95.064%**.

### Output do bloco de treinamento

<details>
  <summary>Click to expand!</summary>
  
  ```text
Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
       0/99      14.5G     0.1173    0.02951    0.04212         48        640: 100% 3/3 [00:06<00:00,  2.05s/it]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:03<00:00,  3.60s/it]
                   all         48         51   0.000615      0.185    0.00187   0.000344

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
       1/99      14.5G      0.117     0.0299    0.04352         47        640: 100% 3/3 [00:02<00:00,  1.45it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:02<00:00,  2.44s/it]
                   all         48         51   0.000702      0.207    0.00184   0.000399

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
       2/99      14.5G     0.1091    0.02967    0.04121         52        640: 100% 3/3 [00:01<00:00,  1.65it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.08s/it]
                   all         48         51    0.00143      0.407    0.00296   0.000538

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
       3/99      14.5G    0.09301    0.03038    0.04133         57        640: 100% 3/3 [00:01<00:00,  1.51it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.11it/s]
                   all         48         51    0.00234      0.662    0.00461    0.00125

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
       4/99      14.5G    0.08414    0.02782    0.03717         42        640: 100% 3/3 [00:01<00:00,  1.70it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.23s/it]
                   all         48         51    0.00332      0.925     0.0155    0.00356

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
       5/99      14.5G    0.07755    0.03044    0.03635         61        640: 100% 3/3 [00:02<00:00,  1.50it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.42s/it]
                   all         48         51    0.00338      0.943     0.0431     0.0113

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
       6/99      14.5G    0.07188    0.02928    0.03551         64        640: 100% 3/3 [00:01<00:00,  1.65it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.27it/s]
                   all         48         51     0.0541      0.807      0.176     0.0534

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
       7/99      14.5G    0.06404    0.02723    0.03221         52        640: 100% 3/3 [00:01<00:00,  1.69it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.37it/s]
                   all         48         51      0.276      0.248      0.345      0.119

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
       8/99      14.5G    0.06093    0.02685    0.03196         54        640: 100% 3/3 [00:01<00:00,  1.71it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.40it/s]
                   all         48         51      0.294      0.397      0.384      0.183

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
       9/99      14.5G    0.05552    0.02522    0.03117         52        640: 100% 3/3 [00:01<00:00,  1.53it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.27s/it]
                   all         48         51      0.394       0.83      0.527      0.217

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      10/99      14.5G    0.05127    0.02385     0.0289         63        640: 100% 3/3 [00:02<00:00,  1.50it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.23it/s]
                   all         48         51      0.285      0.563      0.374      0.139

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      11/99      14.5G    0.05089    0.02129    0.02614         55        640: 100% 3/3 [00:01<00:00,  1.68it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.30it/s]
                   all         48         51      0.441      0.788      0.596      0.244

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      12/99      14.5G    0.05039    0.02237     0.0258         64        640: 100% 3/3 [00:01<00:00,  1.70it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.46it/s]
                   all         48         51      0.374      0.493      0.516      0.189

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      13/99      14.5G    0.05247    0.02004     0.0244         59        640: 100% 3/3 [00:01<00:00,  1.70it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.60it/s]
                   all         48         51      0.454      0.751      0.588      0.219

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      14/99      14.5G    0.05274    0.01739    0.02377         44        640: 100% 3/3 [00:02<00:00,  1.47it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.03s/it]
                   all         48         51      0.445       0.73      0.651      0.368

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      15/99      14.5G    0.05039    0.01816    0.02187         53        640: 100% 3/3 [00:02<00:00,  1.49it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.03it/s]
                   all         48         51      0.756      0.556      0.687      0.294

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      16/99      14.5G    0.04991    0.01858    0.02139         56        640: 100% 3/3 [00:01<00:00,  1.59it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.69it/s]
                   all         48         51      0.422      0.766      0.689      0.324

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      17/99      14.5G    0.04662    0.01747    0.01999         44        640: 100% 3/3 [00:01<00:00,  1.66it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.65it/s]
                   all         48         51       0.52      0.835      0.794      0.369

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      18/99      14.5G    0.04795    0.01678    0.01661         39        640: 100% 3/3 [00:01<00:00,  1.65it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.61it/s]
                   all         48         51      0.481      0.712      0.768      0.359

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      19/99      14.5G    0.05038    0.01551    0.01666         45        640: 100% 3/3 [00:02<00:00,  1.47it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.10s/it]
                   all         48         51      0.613      0.751      0.789      0.346

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      20/99      14.5G    0.04957    0.01683     0.0145         57        640: 100% 3/3 [00:02<00:00,  1.46it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.15it/s]
                   all         48         51      0.678      0.728      0.777      0.369

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      21/99      14.5G    0.04895      0.016    0.01241         61        640: 100% 3/3 [00:01<00:00,  1.66it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.44it/s]
                   all         48         51      0.521      0.866      0.735      0.241

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      22/99      14.5G    0.04981    0.01568    0.01368         60        640: 100% 3/3 [00:01<00:00,  1.65it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.62it/s]
                   all         48         51      0.672      0.883      0.836      0.429

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      23/99      14.5G    0.04714     0.0155    0.01011         66        640: 100% 3/3 [00:01<00:00,  1.68it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.56it/s]
                   all         48         51      0.697      0.555      0.695      0.307

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      24/99      14.5G     0.0503     0.0141    0.01024         57        640: 100% 3/3 [00:02<00:00,  1.48it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.10s/it]
                   all         48         51      0.608      0.754       0.76      0.443

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      25/99      14.5G    0.04941    0.01338    0.00806         55        640: 100% 3/3 [00:02<00:00,  1.46it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.53it/s]
                   all         48         51      0.647       0.85      0.855      0.425

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      26/99      14.5G    0.04874    0.01292   0.007769         46        640: 100% 3/3 [00:01<00:00,  1.59it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.61it/s]
                   all         48         51      0.837      0.799      0.889       0.39

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      27/99      14.5G    0.04854     0.0124   0.005404         52        640: 100% 3/3 [00:01<00:00,  1.68it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.69it/s]
                   all         48         51       0.75      0.831      0.854       0.41

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      28/99      14.5G    0.04928    0.01354   0.007839         67        640: 100% 3/3 [00:01<00:00,  1.68it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.75it/s]
                   all         48         51      0.826      0.904      0.822      0.353

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      29/99      14.5G    0.04598    0.01249   0.007299         50        640: 100% 3/3 [00:02<00:00,  1.47it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.12s/it]
                   all         48         51      0.713      0.747      0.761      0.309

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      30/99      14.5G    0.04935    0.01215   0.007643         50        640: 100% 3/3 [00:02<00:00,  1.47it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.22it/s]
                   all         48         51      0.776      0.865      0.843      0.438

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      31/99      14.5G    0.04864    0.01289   0.005101         55        640: 100% 3/3 [00:01<00:00,  1.64it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.51it/s]
                   all         48         51      0.663      0.884      0.824       0.43

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      32/99      14.5G    0.05004    0.01238   0.004848         50        640: 100% 3/3 [00:01<00:00,  1.67it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.60it/s]
                   all         48         51      0.775      0.872       0.84      0.464

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      33/99      14.5G      0.043    0.01213   0.004578         46        640: 100% 3/3 [00:01<00:00,  1.64it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.59it/s]
                   all         48         51      0.784      0.903      0.902      0.456

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      34/99      14.5G    0.04486    0.01146   0.004531         57        640: 100% 3/3 [00:01<00:00,  1.50it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.02s/it]
                   all         48         51      0.669      0.878      0.813      0.465

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      35/99      14.5G    0.04645    0.01072   0.006159         52        640: 100% 3/3 [00:02<00:00,  1.46it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.30it/s]
                   all         48         51      0.842      0.903      0.909      0.542

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      36/99      14.5G    0.03973    0.01094   0.003959         60        640: 100% 3/3 [00:01<00:00,  1.66it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.61it/s]
                   all         48         51      0.761      0.943      0.879      0.482

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      37/99      14.5G    0.04033    0.01163    0.00376         63        640: 100% 3/3 [00:01<00:00,  1.64it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.57it/s]
                   all         48         51      0.708      0.913      0.828      0.437

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      38/99      14.5G    0.04057    0.01205   0.003636         72        640: 100% 3/3 [00:01<00:00,  1.65it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.62it/s]
                   all         48         51      0.673      0.925       0.84      0.477

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      39/99      14.5G    0.03825    0.01124   0.003696         61        640: 100% 3/3 [00:02<00:00,  1.48it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.06s/it]
                   all         48         51      0.794      0.895       0.87      0.404

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      40/99      14.5G    0.03809    0.01124   0.004317         51        640: 100% 3/3 [00:02<00:00,  1.43it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.48it/s]
                   all         48         51      0.885      0.925      0.936      0.541

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      41/99      14.5G    0.03864    0.01028   0.003073         57        640: 100% 3/3 [00:01<00:00,  1.66it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.56it/s]
                   all         48         51      0.899      0.911      0.936      0.517

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      42/99      14.5G    0.03765   0.009781    0.00389         54        640: 100% 3/3 [00:01<00:00,  1.65it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.52it/s]
                   all         48         51       0.81      0.897       0.88       0.53

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      43/99      14.5G    0.03712    0.01001   0.003314         60        640: 100% 3/3 [00:01<00:00,  1.67it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.64it/s]
                   all         48         51       0.71      0.878      0.845      0.486

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      44/99      14.5G    0.03547    0.01018   0.002678         54        640: 100% 3/3 [00:02<00:00,  1.49it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.10s/it]
                   all         48         51      0.849      0.863       0.89      0.571

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      45/99      14.5G    0.03625   0.009573    0.00311         49        640: 100% 3/3 [00:02<00:00,  1.45it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.51it/s]
                   all         48         51      0.868      0.888      0.943      0.579

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      46/99      14.5G    0.03042   0.009131    0.00248         48        640: 100% 3/3 [00:01<00:00,  1.66it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.67it/s]
                   all         48         51      0.964      0.912      0.944      0.528

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      47/99      14.5G    0.03487   0.009607   0.002785         63        640: 100% 3/3 [00:01<00:00,  1.67it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.58it/s]
                   all         48         51      0.871      0.917      0.923      0.633

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      48/99      14.5G    0.03493    0.01027   0.003169         56        640: 100% 3/3 [00:01<00:00,  1.65it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.23it/s]
                   all         48         51       0.95      0.925      0.941      0.623

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      49/99      14.5G    0.03322   0.009798    0.00277         54        640: 100% 3/3 [00:01<00:00,  1.51it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.04s/it]
                   all         48         51       0.98       0.92      0.941      0.626

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      50/99      14.5G    0.03267   0.009513   0.003097         65        640: 100% 3/3 [00:01<00:00,  1.52it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.19it/s]
                   all         48         51       0.94      0.922      0.943      0.633

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      51/99      14.5G    0.03159    0.00903     0.0027         60        640: 100% 3/3 [00:01<00:00,  1.60it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.64it/s]
                   all         48         51       0.96      0.924      0.946      0.655

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      52/99      14.5G    0.03347   0.009841   0.002704         63        640: 100% 3/3 [00:01<00:00,  1.63it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.54it/s]
                   all         48         51      0.954      0.928      0.944      0.656

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      53/99      14.5G    0.03157    0.00901    0.00293         55        640: 100% 3/3 [00:01<00:00,  1.58it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.10it/s]
                   all         48         51       0.94      0.922      0.942      0.653

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      54/99      14.5G    0.02962   0.008739   0.002884         53        640: 100% 3/3 [00:02<00:00,  1.47it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.03s/it]
                   all         48         51      0.944      0.909       0.94      0.663

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      55/99      14.5G    0.02942   0.008434   0.002522         47        640: 100% 3/3 [00:01<00:00,  1.58it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.64it/s]
                   all         48         51      0.933      0.913      0.935      0.625

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      56/99      14.5G    0.02839   0.008242   0.002123         46        640: 100% 3/3 [00:01<00:00,  1.66it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.68it/s]
                   all         48         51      0.944      0.903      0.936      0.674

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      57/99      14.5G    0.03099   0.008603    0.00237         48        640: 100% 3/3 [00:01<00:00,  1.62it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.65it/s]
                   all         48         51      0.944        0.9       0.93       0.66

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      58/99      14.5G     0.0309   0.008751   0.002476         58        640: 100% 3/3 [00:01<00:00,  1.56it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.07s/it]
                   all         48         51      0.953      0.921       0.93      0.645

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      59/99      14.5G     0.0281   0.009137   0.001898         58        640: 100% 3/3 [00:02<00:00,  1.49it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.15it/s]
                   all         48         51      0.964      0.925      0.933      0.657

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      60/99      14.5G    0.02969    0.01001   0.002004         67        640: 100% 3/3 [00:01<00:00,  1.59it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.52it/s]
                   all         48         51       0.95      0.908      0.932      0.663

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      61/99      14.5G    0.03051   0.009829   0.002544         64        640: 100% 3/3 [00:01<00:00,  1.65it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.65it/s]
                   all         48         51      0.928      0.943      0.936      0.615

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      62/99      14.5G    0.02698   0.008735   0.001796         52        640: 100% 3/3 [00:01<00:00,  1.69it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.69it/s]
                   all         48         51       0.96      0.943       0.94       0.65

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      63/99      14.5G     0.0257   0.008141   0.002893         49        640: 100% 3/3 [00:02<00:00,  1.48it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.17it/s]
                   all         48         51      0.953      0.943      0.944      0.691

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      64/99      14.5G    0.02593   0.008735   0.001888         54        640: 100% 3/3 [00:02<00:00,  1.47it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.34it/s]
                   all         48         51       0.95      0.943      0.938      0.706

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      65/99      14.5G    0.02573   0.009205    0.00205         69        640: 100% 3/3 [00:01<00:00,  1.64it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.68it/s]
                   all         48         51      0.952      0.943      0.929      0.672

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      66/99      14.5G    0.02694    0.00972   0.001523         63        640: 100% 3/3 [00:01<00:00,  1.63it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.67it/s]
                   all         48         51      0.937      0.932      0.934      0.655

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      67/99      14.5G     0.0258   0.007903   0.001781         49        640: 100% 3/3 [00:01<00:00,  1.65it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.50it/s]
                   all         48         51      0.951      0.924      0.923      0.687

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      68/99      14.5G    0.02381   0.007992   0.001365         53        640: 100% 3/3 [00:02<00:00,  1.47it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.05s/it]
                   all         48         51       0.95      0.924      0.918      0.667

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      69/99      14.5G    0.02593   0.007629   0.001506         50        640: 100% 3/3 [00:02<00:00,  1.45it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.44it/s]
                   all         48         51       0.95      0.924      0.922      0.672

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      70/99      14.5G    0.02321    0.00833   0.001982         49        640: 100% 3/3 [00:01<00:00,  1.59it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.75it/s]
                   all         48         51      0.948      0.924      0.922      0.656

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      71/99      14.5G    0.02485   0.008585   0.001422         64        640: 100% 3/3 [00:01<00:00,  1.66it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.63it/s]
                   all         48         51      0.951      0.924      0.928      0.659

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      72/99      14.5G    0.02444   0.008072   0.001673         54        640: 100% 3/3 [00:01<00:00,  1.67it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.53it/s]
                   all         48         51      0.948      0.943      0.935      0.695

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      73/99      14.5G    0.02324   0.007747   0.001515         56        640: 100% 3/3 [00:01<00:00,  1.51it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.11s/it]
                   all         48         51      0.949      0.943      0.933       0.69

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      74/99      14.5G    0.02518   0.007867   0.002684         49        640: 100% 3/3 [00:02<00:00,  1.46it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.36it/s]
                   all         48         51      0.945      0.939      0.941      0.683

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      75/99      14.5G    0.02489   0.007663   0.001348         49        640: 100% 3/3 [00:01<00:00,  1.59it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.77it/s]
                   all         48         51      0.954       0.93      0.941      0.711

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      76/99      14.5G     0.0249   0.007882   0.001491         58        640: 100% 3/3 [00:01<00:00,  1.65it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.59it/s]
                   all         48         51      0.953      0.935      0.941      0.699

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      77/99      14.5G    0.02338   0.008244    0.00121         53        640: 100% 3/3 [00:01<00:00,  1.64it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.63it/s]
                   all         48         51      0.966      0.935      0.946      0.704

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      78/99      14.5G    0.02188   0.008403   0.002326         60        640: 100% 3/3 [00:02<00:00,  1.49it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.02it/s]
                   all         48         51      0.965      0.935      0.949      0.711

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      79/99      14.5G    0.02088   0.008667   0.001328         65        640: 100% 3/3 [00:02<00:00,  1.48it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.38it/s]
                   all         48         51      0.964      0.937       0.95      0.708

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      80/99      14.5G    0.02104   0.007684   0.001405         53        640: 100% 3/3 [00:01<00:00,  1.62it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.68it/s]
                   all         48         51      0.965      0.943      0.953      0.714

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      81/99      14.5G    0.02185   0.007261  0.0009642         41        640: 100% 3/3 [00:01<00:00,  1.67it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.56it/s]
                   all         48         51      0.966      0.943      0.954      0.715

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      82/99      14.5G    0.02203   0.008324   0.001523         53        640: 100% 3/3 [00:01<00:00,  1.65it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.66it/s]
                   all         48         51      0.966      0.943      0.952      0.708

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      83/99      14.5G    0.02273   0.007898   0.001543         56        640: 100% 3/3 [00:01<00:00,  1.54it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.04it/s]
                   all         48         51      0.968      0.943      0.953      0.722

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      84/99      14.5G    0.01977   0.008448   0.001158         58        640: 100% 3/3 [00:02<00:00,  1.45it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.80it/s]
                   all         48         51      0.968      0.943      0.949      0.693

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      85/99      14.5G    0.01954   0.008231  0.0009324         59        640: 100% 3/3 [00:02<00:00,  1.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.14s/it]
                   all         48         51      0.954      0.943      0.944       0.69

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      86/99      14.5G    0.01957   0.007949   0.002212         69        640: 100% 3/3 [00:02<00:00,  1.50it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.15it/s]
                   all         48         51      0.954      0.941      0.944      0.713

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      87/99      14.5G    0.01812   0.008274   0.001032         62        640: 100% 3/3 [00:02<00:00,  1.50it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.16s/it]
                   all         48         51      0.941      0.943      0.944      0.704

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      88/99      14.5G    0.02107   0.007662   0.001313         46        640: 100% 3/3 [00:02<00:00,  1.44it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.03it/s]
                   all         48         51      0.956      0.943      0.947      0.698

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      89/99      14.5G    0.01872   0.007213  0.0008376         46        640: 100% 3/3 [00:01<00:00,  1.60it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.80it/s]
                   all         48         51      0.946      0.943      0.946      0.708

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      90/99      14.5G    0.01936   0.007031    0.00117         40        640: 100% 3/3 [00:01<00:00,  1.64it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.66it/s]
                   all         48         51      0.949      0.943      0.948      0.708

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      91/99      14.5G    0.02222   0.007219   0.002038         56        640: 100% 3/3 [00:01<00:00,  1.63it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.64it/s]
                   all         48         51      0.949      0.943      0.947      0.717

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      92/99      14.5G    0.02094   0.007486   0.001074         54        640: 100% 3/3 [00:01<00:00,  1.57it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.08s/it]
                   all         48         51      0.952      0.943      0.952      0.693

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      93/99      14.5G    0.01977   0.007307   0.001149         45        640: 100% 3/3 [00:02<00:00,  1.48it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.04it/s]
                   all         48         51      0.969      0.943      0.953      0.712

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      94/99      14.5G    0.01792   0.007574  0.0009988         61        640: 100% 3/3 [00:01<00:00,  1.56it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.62it/s]
                   all         48         51       0.97      0.946      0.954       0.69

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      95/99      14.5G    0.01722    0.00717  0.0005925         56        640: 100% 3/3 [00:01<00:00,  1.64it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.80it/s]
                   all         48         51      0.971      0.946      0.954      0.715

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      96/99      14.5G    0.01958   0.007926   0.002278         55        640: 100% 3/3 [00:01<00:00,  1.64it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.57it/s]
                   all         48         51      0.971      0.945      0.954      0.703

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      97/99      14.5G    0.01979    0.00745   0.002163         50        640: 100% 3/3 [00:01<00:00,  1.52it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.10it/s]
                   all         48         51      0.971      0.943      0.953      0.718

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      98/99      14.5G    0.01779   0.006418   0.001656         53        640: 100% 3/3 [00:02<00:00,  1.48it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.05it/s]
                   all         48         51       0.97      0.941      0.952      0.721

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      99/99      14.5G    0.01798   0.007337   0.001713         53        640: 100% 3/3 [00:01<00:00,  1.60it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.56it/s]
                   all         48         51      0.969      0.941      0.952       0.72

100 epochs completed in 0.097 hours.
Optimizer stripped from runs/train/exp/weights/last.pt, 14.5MB
Optimizer stripped from runs/train/exp/weights/best.pt, 14.5MB

Validating runs/train/exp/weights/best.pt...
Fusing layers... 
Model summary: 157 layers, 7018216 parameters, 0 gradients, 15.8 GFLOPs
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.79it/s]
                   all         48         51      0.968      0.943      0.951       0.72
                  azul         48         18      0.936      0.889      0.882      0.691
                 verde         48         17      0.988      0.941      0.975      0.663
              vermelha         48         16      0.979          1      0.995      0.805
Results saved to runs/train/exp
wandb: Waiting for W&B process to finish... (success).
wandb: 
wandb: Run history:
wandb:      metrics/mAP_0.5 ▁▁▁▄▄▅▆▇▇▆▇▇▇██▇█▇██████████████████████
wandb: metrics/mAP_0.5:0.95 ▁▁▁▂▂▃▄▅▅▄▅▄▅▅▆▆▆▆▆▇▇▇█▇▇█▇█▇███████████
wandb:    metrics/precision ▁▁▁▃▃▄▆▅▆▆▆▇▇▇▇▆▇▆██████████████████████
wandb:       metrics/recall ▁▃█▂▄▄▄▇▆▄▇█▇████▇██████████████████████
wandb:       train/box_loss █▇▅▄▃▃▃▃▃▃▃▃▃▃▃▃▂▂▂▂▂▂▂▂▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁
wandb:       train/cls_loss ██▇▆▆▅▅▄▃▃▂▂▂▂▂▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
wandb:       train/obj_loss ███▇▆▆▄▄▄▄▃▃▂▂▂▂▂▂▂▂▂▂▁▁▂▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁
wandb:         val/box_loss █▆▄▃▄▃▃▃▃▃▃▃▂▃▂▂▂▂▂▂▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
wandb:         val/cls_loss ██▇▇▆▆▄▄▃▂▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
wandb:         val/obj_loss █▇▆▅▅▅▃▃▂▂▂▂▁▁▁▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
wandb:                x/lr0 ██▇▇▆▆▅▅▄▄▃▃▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
wandb:                x/lr1 ▁▂▃▃▄▄▅▆▆▆▇▇████▇▇▇▇▆▆▆▅▅▅▅▄▄▄▄▃▃▃▂▂▂▂▁▁
wandb:                x/lr2 ▁▂▃▃▄▄▅▆▆▆▇▇████▇▇▇▇▆▆▆▅▅▅▅▄▄▄▄▃▃▃▂▂▂▂▁▁
wandb: 
wandb: Run summary:
wandb:           best/epoch 83
wandb:         best/mAP_0.5 0.95346
wandb:    best/mAP_0.5:0.95 0.72164
wandb:       best/precision 0.96762
wandb:          best/recall 0.94336
wandb:      metrics/mAP_0.5 0.95064
wandb: metrics/mAP_0.5:0.95 0.71958
wandb:    metrics/precision 0.96762
wandb:       metrics/recall 0.94336
wandb:       train/box_loss 0.01798
wandb:       train/cls_loss 0.00171
wandb:       train/obj_loss 0.00734
wandb:         val/box_loss 0.01577
wandb:         val/cls_loss 0.00094
wandb:         val/obj_loss 0.00473
wandb:                x/lr0 0.0003
wandb:                x/lr1 0.0003
wandb:                x/lr2 0.0003
  ```
</details>

### Evidências do treinamento

Nessa seção você deve colocar qualquer evidência do treinamento, como por exemplo gráficos de perda, performance, matriz de confusão etc.

Exemplo de adição de imagem:
![Metrics](https://wandb.ai/amps/YOLOv5/runs/b2fqd4dt?workspace=user-amps)

## Roboflow

Nessa seção deve colocar o link para acessar o dataset no Roboflow

Exemplo de link: [Dataset Roboflow](https://universe.roboflow.com/classificao-de-imagens/classificacao-de-papeleiras/dataset/2)

## HuggingFace

Nessa seção você deve publicar o link para o HuggingFace
