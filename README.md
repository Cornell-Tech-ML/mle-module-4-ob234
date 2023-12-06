[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/5gWs3A8E)
# MiniTorch Module 4

<img src="https://minitorch.github.io/minitorch.svg" width="50%">

* Docs: https://minitorch.github.io/

* Overview: https://minitorch.github.io/module4.html

This module requires `fast_ops.py`, `cuda_ops.py`, `scalar.py`, `tensor_functions.py`, `tensor_data.py`, `tensor_ops.py`, `operators.py`, `module.py`, and `autodiff.py` from Module 3.


Additionally you will need to install and download the MNist library.

(On Mac, this may require installing the `wget` command)

```
pip install python-mnist
mnist_get_data.sh
```


* Tests:

```
python run_tests.py
```

This assignment requires the following files from the previous assignments. You can get these by running

```bash
python sync_previous_module.py previous-module-dir current-module-dir
```

The files that will be synced are:

        minitorch/tensor_data.py minitorch/tensor_functions.py minitorch/tensor_ops.py minitorch/fast_ops.py minitorch/cuda_ops.py minitorch/operators.py minitorch/module.py minitorch/autodiff.py minitorch/module.py project/run_manual.py project/run_scalar.py project/run_tensor.py project/run_fast_tensor.py project/parallel_check.py tests/test_tensor_general.py

--- 

### Sentiment Logs 
``` 
Epoch 1, loss 31.442293461333218, train accuracy: 51.33%
Validation accuracy: 48.00%
Best Valid accuracy: 48.00%
Epoch 2, loss 31.294893853512345, train accuracy: 51.11%
Validation accuracy: 49.00%
Best Valid accuracy: 49.00%
Epoch 3, loss 31.02559191936211, train accuracy: 54.22%
Validation accuracy: 51.00%
Best Valid accuracy: 51.00%
Epoch 4, loss 30.93054891346985, train accuracy: 51.78%
Validation accuracy: 54.00%
Best Valid accuracy: 54.00%
Epoch 5, loss 30.742713393932245, train accuracy: 54.89%
Validation accuracy: 61.00%
Best Valid accuracy: 61.00%
Epoch 6, loss 30.43343961109259, train accuracy: 53.78%
Validation accuracy: 52.00%
Best Valid accuracy: 61.00%
Epoch 7, loss 30.349447158736574, train accuracy: 59.11%
Validation accuracy: 51.00%
Best Valid accuracy: 61.00%
Epoch 8, loss 29.877914933661007, train accuracy: 62.67%
Validation accuracy: 70.00%
Best Valid accuracy: 70.00%
Epoch 9, loss 29.75851971154899, train accuracy: 63.78%
Validation accuracy: 63.00%
Best Valid accuracy: 70.00%
Epoch 10, loss 29.387980714463012, train accuracy: 66.67%
Validation accuracy: 56.00%
Best Valid accuracy: 70.00%
Epoch 11, loss 28.758022412546858, train accuracy: 68.22%
Validation accuracy: 66.00%
Best Valid accuracy: 70.00%
Epoch 12, loss 28.42863096107577, train accuracy: 68.00%
Validation accuracy: 65.00%
Best Valid accuracy: 70.00%
Epoch 13, loss 28.156300903425624, train accuracy: 70.22%
Validation accuracy: 64.00%
Best Valid accuracy: 70.00%
Epoch 14, loss 28.01171887664742, train accuracy: 66.44%
Validation accuracy: 64.00%
Best Valid accuracy: 70.00%
Epoch 15, loss 27.29479845700351, train accuracy: 72.44%
Validation accuracy: 71.00%
Best Valid accuracy: 71.00%
Epoch 16, loss 26.656736594717373, train accuracy: 71.11%
Validation accuracy: 68.00%
Best Valid accuracy: 71.00%
Epoch 17, loss 26.132717814122692, train accuracy: 72.22%
Validation accuracy: 53.00%
Best Valid accuracy: 71.00%
Epoch 18, loss 25.537760688735258, train accuracy: 75.33%
Validation accuracy: 65.00%
Best Valid accuracy: 71.00%
Epoch 19, loss 24.588343911647087, train accuracy: 77.11%
Validation accuracy: 67.00%
Best Valid accuracy: 71.00%
Epoch 20, loss 23.86920390308913, train accuracy: 75.33%
Validation accuracy: 66.00%
Best Valid accuracy: 71.00%
Epoch 21, loss 23.28520753408734, train accuracy: 76.00%
Validation accuracy: 74.00%
Best Valid accuracy: 74.00%
Epoch 22, loss 22.56579454181388, train accuracy: 77.33%
Validation accuracy: 62.00%
Best Valid accuracy: 74.00%
Epoch 23, loss 22.113892761543056, train accuracy: 78.22%
Validation accuracy: 64.00%
Best Valid accuracy: 74.00%
Epoch 24, loss 21.778802911571276, train accuracy: 77.11%
Validation accuracy: 66.00%
Best Valid accuracy: 74.00%
Epoch 25, loss 21.125834448504584, train accuracy: 76.22%
Validation accuracy: 70.00%
Best Valid accuracy: 74.00%
Epoch 26, loss 20.58354282702096, train accuracy: 76.67%
Validation accuracy: 67.00%
Best Valid accuracy: 74.00%
Epoch 27, loss 19.566760472175602, train accuracy: 78.44%
Validation accuracy: 65.00%
Best Valid accuracy: 74.00%
Epoch 28, loss 19.464403098605853, train accuracy: 80.44%
Validation accuracy: 61.00%
Best Valid accuracy: 74.00%
Epoch 29, loss 18.96243606226827, train accuracy: 80.44%
Validation accuracy: 71.00%
Best Valid accuracy: 74.00%
Epoch 30, loss 18.623161647331383, train accuracy: 81.33%
Validation accuracy: 72.00%
Best Valid accuracy: 74.00%
Epoch 31, loss 18.03083157984457, train accuracy: 80.89%
Validation accuracy: 70.00%
Best Valid accuracy: 74.00%
Epoch 32, loss 17.251299842351493, train accuracy: 82.44%
Validation accuracy: 69.00%
Best Valid accuracy: 74.00%
Epoch 33, loss 16.145292593998125, train accuracy: 84.00%
Validation accuracy: 72.00%
Best Valid accuracy: 74.00%
Epoch 34, loss 16.513987296524192, train accuracy: 84.89%
Validation accuracy: 62.00%
Best Valid accuracy: 74.00%
Epoch 35, loss 16.990134211769735, train accuracy: 79.56%
Validation accuracy: 66.00%
Best Valid accuracy: 74.00%
Epoch 36, loss 15.260928024661604, train accuracy: 82.22%
Validation accuracy: 66.00%
Best Valid accuracy: 74.00%
Epoch 37, loss 15.24850375636374, train accuracy: 85.11%
Validation accuracy: 65.00%
Best Valid accuracy: 74.00%
Epoch 38, loss 14.404424598455844, train accuracy: 86.00%
Validation accuracy: 70.00%
Best Valid accuracy: 74.00%
Epoch 39, loss 14.825820463515111, train accuracy: 84.44%
Validation accuracy: 77.00%
Best Valid accuracy: 77.00%
Epoch 40, loss 14.152969719087483, train accuracy: 87.56%
Validation accuracy: 69.00%
Best Valid accuracy: 77.00%
Epoch 41, loss 13.478618866911932, train accuracy: 87.11%
Validation accuracy: 70.00%
Best Valid accuracy: 77.00%
Epoch 42, loss 14.508586757779723, train accuracy: 82.44%
Validation accuracy: 75.00%
Best Valid accuracy: 77.00%
Epoch 43, loss 13.237731165168613, train accuracy: 87.11%
Validation accuracy: 65.00%
Best Valid accuracy: 77.00%
Epoch 44, loss 12.717372975637634, train accuracy: 87.56%
Validation accuracy: 66.00%
Best Valid accuracy: 77.00%
Epoch 45, loss 13.903406160875742, train accuracy: 83.33%
Validation accuracy: 66.00%
Best Valid accuracy: 77.00%
Epoch 46, loss 13.167298112146574, train accuracy: 86.00%
Validation accuracy: 75.00%
Best Valid accuracy: 77.00%
Epoch 47, loss 14.235600168149512, train accuracy: 81.78%
Validation accuracy: 73.00%
Best Valid accuracy: 77.00%
Epoch 48, loss 13.499470546202398, train accuracy: 84.89%
Validation accuracy: 66.00%
Best Valid accuracy: 77.00%
Epoch 49, loss 12.534231806388808, train accuracy: 85.78%
Validation accuracy: 65.00%
Best Valid accuracy: 77.00%
Epoch 50, loss 11.52735403738233, train accuracy: 88.22%
Validation accuracy: 67.00%
Best Valid accuracy: 77.00%
Epoch 51, loss 12.110887945017351, train accuracy: 86.67%
Validation accuracy: 65.00%
Best Valid accuracy: 77.00%
Epoch 52, loss 11.399609454021968, train accuracy: 88.22%
Validation accuracy: 67.00%
Best Valid accuracy: 77.00%
Epoch 53, loss 12.285644177110612, train accuracy: 86.67%
Validation accuracy: 62.00%
Best Valid accuracy: 77.00%
Epoch 54, loss 11.990861112153524, train accuracy: 86.00%
Validation accuracy: 64.00%
Best Valid accuracy: 77.00%
Epoch 55, loss 11.644218443318422, train accuracy: 84.67%
Validation accuracy: 61.00%
Best Valid accuracy: 77.00%
Epoch 56, loss 11.194860452287143, train accuracy: 86.67%
Validation accuracy: 69.00%
Best Valid accuracy: 77.00%
Epoch 57, loss 12.276346061630942, train accuracy: 85.78%
Validation accuracy: 63.00%
Best Valid accuracy: 77.00%
Epoch 58, loss 10.828966720900643, train accuracy: 86.67%
Validation accuracy: 62.00%
Best Valid accuracy: 77.00%
Epoch 59, loss 11.268230946526115, train accuracy: 87.56%
Validation accuracy: 57.00%
Best Valid accuracy: 77.00%
Epoch 60, loss 11.388524727621595, train accuracy: 84.44%
Validation accuracy: 63.00%
Best Valid accuracy: 77.00%
Epoch 61, loss 10.728026665157916, train accuracy: 86.67%
Validation accuracy: 66.00%
Best Valid accuracy: 77.00%
Epoch 62, loss 10.80834925996384, train accuracy: 87.33%
Validation accuracy: 59.00%
Best Valid accuracy: 77.00%
Epoch 63, loss 10.597496676585159, train accuracy: 84.22%
Validation accuracy: 70.00%
Best Valid accuracy: 77.00%
Epoch 64, loss 9.900379032039478, train accuracy: 87.11%
Validation accuracy: 59.00%
Best Valid accuracy: 77.00%
Epoch 65, loss 9.827313445309906, train accuracy: 89.11%
Validation accuracy: 64.00%
Best Valid accuracy: 77.00%
Epoch 66, loss 9.332521253105966, train accuracy: 86.44%
Validation accuracy: 65.00%
Best Valid accuracy: 77.00%
Epoch 67, loss 10.502969284685994, train accuracy: 87.33%
Validation accuracy: 61.00%
Best Valid accuracy: 77.00%
Epoch 68, loss 10.560987321379246, train accuracy: 87.33%
Validation accuracy: 63.00%
Best Valid accuracy: 77.00%
Epoch 69, loss 9.70084791936524, train accuracy: 88.67%
Validation accuracy: 61.00%
Best Valid accuracy: 77.00%
Epoch 70, loss 9.669283838123015, train accuracy: 88.00%
Validation accuracy: 63.00%
Best Valid accuracy: 77.00%
Epoch 71, loss 10.26597324183381, train accuracy: 84.89%
Validation accuracy: 68.00%
Best Valid accuracy: 77.00%
Epoch 72, loss 10.184440630285685, train accuracy: 86.00%
Validation accuracy: 67.00%
Best Valid accuracy: 77.00%
Epoch 73, loss 10.239357012934704, train accuracy: 85.11%
Validation accuracy: 68.00%
Best Valid accuracy: 77.00%
Epoch 74, loss 9.611706356260509, train accuracy: 85.78%
Validation accuracy: 58.00%
Best Valid accuracy: 77.00%
Epoch 75, loss 9.61320616005806, train accuracy: 87.11%
Validation accuracy: 64.00%
Best Valid accuracy: 77.00%
Epoch 76, loss 8.732185165054316, train accuracy: 88.44%
Validation accuracy: 67.00%
Best Valid accuracy: 77.00%
Epoch 77, loss 10.0171569712718, train accuracy: 86.22%
Validation accuracy: 67.00%
Best Valid accuracy: 77.00%
Epoch 78, loss 9.602206367968677, train accuracy: 87.56%
Validation accuracy: 68.00%
Best Valid accuracy: 77.00%
Epoch 79, loss 9.852834833643003, train accuracy: 85.11%
Validation accuracy: 74.00%
Best Valid accuracy: 77.00%
Epoch 80, loss 9.344273906761542, train accuracy: 86.00%
Validation accuracy: 69.00%
Best Valid accuracy: 77.00%
Epoch 81, loss 8.715213807953381, train accuracy: 88.00%
Validation accuracy: 68.00%
Best Valid accuracy: 77.00%
Epoch 82, loss 9.338792042913454, train accuracy: 86.22%
Validation accuracy: 67.00%
Best Valid accuracy: 77.00%
Epoch 83, loss 9.781620676687467, train accuracy: 87.56%
Validation accuracy: 67.00%
Best Valid accuracy: 77.00%
Epoch 84, loss 9.168695795682444, train accuracy: 86.00%
Validation accuracy: 63.00%
Best Valid accuracy: 77.00%
Epoch 85, loss 8.286186231652312, train accuracy: 88.67%
Validation accuracy: 64.00%
Best Valid accuracy: 77.00%
Epoch 86, loss 9.0199485470703, train accuracy: 86.67%
Validation accuracy: 62.00%
Best Valid accuracy: 77.00%
Epoch 87, loss 8.808349566923697, train accuracy: 85.33%
Validation accuracy: 61.00%
Best Valid accuracy: 77.00%
Epoch 88, loss 9.188244627598872, train accuracy: 87.78%
Validation accuracy: 60.00%
Best Valid accuracy: 77.00%
Epoch 89, loss 9.682606319299598, train accuracy: 89.33%
Validation accuracy: 65.00%
Best Valid accuracy: 77.00%
Epoch 90, loss 8.303682817913653, train accuracy: 87.56%
Validation accuracy: 71.00%
Best Valid accuracy: 77.00%
Epoch 91, loss 7.922971161181617, train accuracy: 89.33%
Validation accuracy: 70.00%
Best Valid accuracy: 77.00%
Epoch 92, loss 9.251614487208268, train accuracy: 85.78%
Validation accuracy: 65.00%
Best Valid accuracy: 77.00%
Epoch 93, loss 10.527577057190198, train accuracy: 83.11%
Validation accuracy: 65.00%
Best Valid accuracy: 77.00%
Epoch 94, loss 9.114433017937555, train accuracy: 85.56%
Validation accuracy: 64.00%
Best Valid accuracy: 77.00%
Epoch 95, loss 9.888154998299441, train accuracy: 85.11%
Validation accuracy: 66.00%
Best Valid accuracy: 77.00%
Epoch 96, loss 8.754019445224987, train accuracy: 88.44%
Validation accuracy: 63.00%
Best Valid accuracy: 77.00%
Epoch 97, loss 8.96786408662675, train accuracy: 87.11%
Validation accuracy: 57.00%
Best Valid accuracy: 77.00%
Epoch 98, loss 9.677059349530271, train accuracy: 85.33%
Validation accuracy: 70.00%
Best Valid accuracy: 77.00%
Epoch 99, loss 8.302994872803847, train accuracy: 87.78%
Validation accuracy: 66.00%
Best Valid accuracy: 77.00%
Epoch 100, loss 9.589327298148133, train accuracy: 86.00%
Validation accuracy: 72.00%
Best Valid accuracy: 77.00%
Epoch 101, loss 9.288044874644443, train accuracy: 87.78%
Validation accuracy: 65.00%
Best Valid accuracy: 77.00%
Epoch 102, loss 7.949893808283715, train accuracy: 88.44%
Validation accuracy: 74.00%
Best Valid accuracy: 77.00%
Epoch 103, loss 8.911956542583523, train accuracy: 87.78%
Validation accuracy: 62.00%
Best Valid accuracy: 77.00%
Epoch 104, loss 8.972003604375896, train accuracy: 89.56%
Validation accuracy: 67.00%
Best Valid accuracy: 77.00%
Epoch 105, loss 9.198506752550621, train accuracy: 84.89%
Validation accuracy: 69.00%
Best Valid accuracy: 77.00%
Epoch 106, loss 8.465387602776643, train accuracy: 86.89%
Validation accuracy: 70.00%
Best Valid accuracy: 77.00%
Epoch 107, loss 9.822669005027697, train accuracy: 86.67%
Validation accuracy: 65.00%
Best Valid accuracy: 77.00%
Epoch 108, loss 8.668982756025446, train accuracy: 86.44%
Validation accuracy: 63.00%
Best Valid accuracy: 77.00%
Epoch 109, loss 7.84806173016211, train accuracy: 88.44%
Validation accuracy: 61.00%
Best Valid accuracy: 77.00%
Epoch 110, loss 8.063346659454247, train accuracy: 87.11%
Validation accuracy: 69.00%
Best Valid accuracy: 77.00%
Epoch 111, loss 8.937095172785842, train accuracy: 86.67%
Validation accuracy: 59.00%
Best Valid accuracy: 77.00%
Epoch 112, loss 8.658009672240633, train accuracy: 87.11%
Validation accuracy: 60.00%
Best Valid accuracy: 77.00%
Epoch 113, loss 8.413186515007784, train accuracy: 88.44%
Validation accuracy: 60.00%
Best Valid accuracy: 77.00%
Epoch 114, loss 9.303415660959432, train accuracy: 86.00%
Validation accuracy: 66.00%
Best Valid accuracy: 77.00%
Epoch 115, loss 8.156231487782334, train accuracy: 88.44%
Validation accuracy: 58.00%
Best Valid accuracy: 77.00%
Epoch 116, loss 8.726349458469995, train accuracy: 85.33%
Validation accuracy: 69.00%
Best Valid accuracy: 77.00%
Epoch 117, loss 9.34873969612163, train accuracy: 86.89%
Validation accuracy: 69.00%
Best Valid accuracy: 77.00%
Epoch 118, loss 9.187098149563203, train accuracy: 84.89%
Validation accuracy: 59.00%
Best Valid accuracy: 77.00%
Epoch 119, loss 8.218610849247364, train accuracy: 89.33%
Validation accuracy: 68.00%
Best Valid accuracy: 77.00%
Epoch 120, loss 8.582423726861665, train accuracy: 86.44%
Validation accuracy: 66.00%
Best Valid accuracy: 77.00%
Epoch 121, loss 7.982159479511187, train accuracy: 88.22%
Validation accuracy: 63.00%
Best Valid accuracy: 77.00%
Epoch 122, loss 7.819381271021173, train accuracy: 89.33%
Validation accuracy: 70.00%
Best Valid accuracy: 77.00%
Epoch 123, loss 9.528189045281742, train accuracy: 84.89%
Validation accuracy: 69.00%
Best Valid accuracy: 77.00%
Epoch 124, loss 8.164759518758197, train accuracy: 88.00%
Validation accuracy: 68.00%
Best Valid accuracy: 77.00%
Epoch 125, loss 8.074066400237534, train accuracy: 86.89%
Validation accuracy: 75.00%
Best Valid accuracy: 77.00%
Epoch 126, loss 9.17964659720486, train accuracy: 85.56%
Validation accuracy: 67.00%
Best Valid accuracy: 77.00%
Epoch 127, loss 9.032974067153958, train accuracy: 86.44%
Validation accuracy: 64.00%
Best Valid accuracy: 77.00%
Epoch 128, loss 8.932181179195217, train accuracy: 86.00%
Validation accuracy: 64.00%
Best Valid accuracy: 77.00%
Epoch 129, loss 8.131813211609913, train accuracy: 87.78%
Validation accuracy: 68.00%
Best Valid accuracy: 77.00%
Epoch 130, loss 8.679524167590753, train accuracy: 86.00%
Validation accuracy: 66.00%
Best Valid accuracy: 77.00%
Epoch 131, loss 8.676005216138563, train accuracy: 88.22%
Validation accuracy: 62.00%
Best Valid accuracy: 77.00%
Epoch 132, loss 7.814368170791667, train accuracy: 88.67%
Validation accuracy: 64.00%
Best Valid accuracy: 77.00%
Epoch 133, loss 7.134616181813409, train accuracy: 90.44%
Validation accuracy: 67.00%
Best Valid accuracy: 77.00%
Epoch 134, loss 7.660961066113381, train accuracy: 89.11%
Validation accuracy: 66.00%
Best Valid accuracy: 77.00%
Epoch 135, loss 8.053544952729471, train accuracy: 88.67%
Validation accuracy: 70.00%
Best Valid accuracy: 77.00%
Epoch 136, loss 9.046412358869057, train accuracy: 85.78%
Validation accuracy: 66.00%
Best Valid accuracy: 77.00%
Epoch 137, loss 8.187933545984334, train accuracy: 86.89%
Validation accuracy: 65.00%
Best Valid accuracy: 77.00%
Epoch 138, loss 8.88172103948333, train accuracy: 89.33%
Validation accuracy: 70.00%
Best Valid accuracy: 77.00%
Epoch 139, loss 8.077284877139952, train accuracy: 87.56%
Validation accuracy: 64.00%
Best Valid accuracy: 77.00%
Epoch 140, loss 8.945127790074494, train accuracy: 85.78%
Validation accuracy: 67.00%
Best Valid accuracy: 77.00%
Epoch 141, loss 7.045349104600607, train accuracy: 89.56%
Validation accuracy: 66.00%
Best Valid accuracy: 77.00%
Epoch 142, loss 9.324831356130849, train accuracy: 86.67%
Validation accuracy: 65.00%
Best Valid accuracy: 77.00%
Epoch 143, loss 8.93717301724145, train accuracy: 87.11%
Validation accuracy: 63.00%
Best Valid accuracy: 77.00%
Epoch 144, loss 8.420192503202939, train accuracy: 87.78%
Validation accuracy: 69.00%
Best Valid accuracy: 77.00%
Epoch 145, loss 8.280533295244224, train accuracy: 88.22%
Validation accuracy: 68.00%
Best Valid accuracy: 77.00%
Epoch 146, loss 8.97378872144486, train accuracy: 84.89%
Validation accuracy: 67.00%
Best Valid accuracy: 77.00%
Epoch 147, loss 9.278215592724333, train accuracy: 85.56%
Validation accuracy: 64.00%
Best Valid accuracy: 77.00%
Epoch 148, loss 8.915668841720382, train accuracy: 84.44%
Validation accuracy: 64.00%
Best Valid accuracy: 77.00%
Epoch 149, loss 7.39604877668277, train accuracy: 89.78%
Validation accuracy: 66.00%
Best Valid accuracy: 77.00%
Epoch 150, loss 7.408291373982576, train accuracy: 88.67%
Validation accuracy: 64.00%
Best Valid accuracy: 77.00%
Epoch 151, loss 8.500337531622467, train accuracy: 86.00%
Validation accuracy: 70.00%
Best Valid accuracy: 77.00%
Epoch 152, loss 8.227015025623393, train accuracy: 84.89%
Validation accuracy: 71.00%
Best Valid accuracy: 77.00%
Epoch 153, loss 8.664337438098617, train accuracy: 85.11%
Validation accuracy: 69.00%
Best Valid accuracy: 77.00%
Epoch 154, loss 8.545446354530963, train accuracy: 87.11%
Validation accuracy: 71.00%
Best Valid accuracy: 77.00%
Epoch 155, loss 8.556170121053945, train accuracy: 88.22%
Validation accuracy: 69.00%
Best Valid accuracy: 77.00%
Epoch 156, loss 7.715673361257072, train accuracy: 88.44%
Validation accuracy: 66.00%
Best Valid accuracy: 77.00%
Epoch 157, loss 8.14491962752128, train accuracy: 84.67%
Validation accuracy: 67.00%
Best Valid accuracy: 77.00%
Epoch 158, loss 7.7783903075185945, train accuracy: 87.78%
Validation accuracy: 72.00%
Best Valid accuracy: 77.00%
Epoch 159, loss 7.747361679991402, train accuracy: 90.44%
Validation accuracy: 68.00%
Best Valid accuracy: 77.00%
Epoch 160, loss 7.913850875474171, train accuracy: 86.89%
Validation accuracy: 64.00%
Best Valid accuracy: 77.00%
Epoch 161, loss 7.116969561395647, train accuracy: 89.78%
Validation accuracy: 61.00%
Best Valid accuracy: 77.00%
Epoch 162, loss 7.399201010161105, train accuracy: 88.67%
Validation accuracy: 62.00%
Best Valid accuracy: 77.00%
Epoch 163, loss 6.513916109569477, train accuracy: 90.00%
Validation accuracy: 63.00%
Best Valid accuracy: 77.00%
Epoch 164, loss 9.004162380737284, train accuracy: 84.22%
Validation accuracy: 65.00%
Best Valid accuracy: 77.00%
Epoch 165, loss 8.711563201413446, train accuracy: 87.11%
Validation accuracy: 67.00%
Best Valid accuracy: 77.00%
Epoch 166, loss 7.614403831276714, train accuracy: 88.22%
Validation accuracy: 71.00%
Best Valid accuracy: 77.00%
Epoch 167, loss 8.651372551633575, train accuracy: 85.11%
Validation accuracy: 64.00%
Best Valid accuracy: 77.00%
Epoch 168, loss 8.27372116702841, train accuracy: 87.11%
Validation accuracy: 68.00%
Best Valid accuracy: 77.00%
Epoch 169, loss 7.544598368055759, train accuracy: 88.44%
Validation accuracy: 63.00%
Best Valid accuracy: 77.00%
Epoch 170, loss 8.664842213439698, train accuracy: 85.33%
Validation accuracy: 71.00%
Best Valid accuracy: 77.00%
Epoch 171, loss 8.482188972362069, train accuracy: 87.11%
Validation accuracy: 72.00%
Best Valid accuracy: 77.00%
Epoch 172, loss 8.94747541487785, train accuracy: 85.78%
Validation accuracy: 68.00%
Best Valid accuracy: 77.00%
Epoch 173, loss 8.401827188230309, train accuracy: 87.33%
Validation accuracy: 63.00%
Best Valid accuracy: 77.00%
Epoch 174, loss 7.813584940097191, train accuracy: 88.44%
Validation accuracy: 72.00%
Best Valid accuracy: 77.00%
Epoch 175, loss 9.834004585479724, train accuracy: 85.33%
Validation accuracy: 71.00%
Best Valid accuracy: 77.00%
Epoch 176, loss 7.28269153496373, train accuracy: 90.22%
Validation accuracy: 63.00%
Best Valid accuracy: 77.00%
Epoch 177, loss 9.353220446983993, train accuracy: 85.56%
Validation accuracy: 77.00%
Best Valid accuracy: 77.00%
Epoch 178, loss 8.744038268232305, train accuracy: 86.00%
Validation accuracy: 69.00%
Best Valid accuracy: 77.00%
Epoch 179, loss 7.789188116919308, train accuracy: 90.00%
Validation accuracy: 67.00%
Best Valid accuracy: 77.00%
Epoch 180, loss 8.419535141999056, train accuracy: 87.33%
Validation accuracy: 67.00%
Best Valid accuracy: 77.00%
Epoch 181, loss 8.93513482738755, train accuracy: 85.56%
Validation accuracy: 67.00%
Best Valid accuracy: 77.00%
Epoch 182, loss 8.65282022817618, train accuracy: 87.56%
Validation accuracy: 65.00%
Best Valid accuracy: 77.00%
Epoch 183, loss 8.692342011599347, train accuracy: 84.44%
Validation accuracy: 69.00%
Best Valid accuracy: 77.00%
Epoch 184, loss 8.932178976165112, train accuracy: 84.44%
Validation accuracy: 64.00%
Best Valid accuracy: 77.00%
Epoch 185, loss 8.349908537801888, train accuracy: 88.00%
Validation accuracy: 71.00%
Best Valid accuracy: 77.00%
Epoch 186, loss 8.051345926479648, train accuracy: 88.89%
Validation accuracy: 74.00%
Best Valid accuracy: 77.00%
Epoch 187, loss 8.386018238508385, train accuracy: 86.67%
Validation accuracy: 68.00%
Best Valid accuracy: 77.00%
Epoch 188, loss 8.430318896800259, train accuracy: 88.00%
Validation accuracy: 57.00%
Best Valid accuracy: 77.00%
Epoch 189, loss 8.212706350071858, train accuracy: 86.89%
Validation accuracy: 66.00%
Best Valid accuracy: 77.00%
Epoch 190, loss 9.024098033525917, train accuracy: 88.22%
Validation accuracy: 70.00%
Best Valid accuracy: 77.00%
Epoch 191, loss 8.880433289650242, train accuracy: 87.56%
Validation accuracy: 67.00%
Best Valid accuracy: 77.00%
Epoch 192, loss 7.119962110983313, train accuracy: 89.33%
Validation accuracy: 67.00%
Best Valid accuracy: 77.00%
Epoch 193, loss 7.8415522494040495, train accuracy: 87.33%
Validation accuracy: 67.00%
Best Valid accuracy: 77.00%
Epoch 194, loss 8.725854965079774, train accuracy: 85.11%
Validation accuracy: 68.00%
Best Valid accuracy: 77.00%
Epoch 195, loss 10.260077105264571, train accuracy: 82.00%
Validation accuracy: 63.00%
Best Valid accuracy: 77.00%
Epoch 196, loss 8.691132720523498, train accuracy: 86.00%
Validation accuracy: 66.00%
Best Valid accuracy: 77.00%
Epoch 197, loss 7.873842701716435, train accuracy: 88.22%
Validation accuracy: 67.00%
Best Valid accuracy: 77.00%
Epoch 198, loss 8.349719038288926, train accuracy: 87.11%
Validation accuracy: 66.00%
Best Valid accuracy: 77.00%
Epoch 199, loss 8.092706135764569, train accuracy: 88.22%
Validation accuracy: 63.00%
Best Valid accuracy: 77.00%
Epoch 200, loss 6.730794746836357, train accuracy: 90.89%
Validation accuracy: 67.00%
Best Valid accuracy: 77.00%
Epoch 201, loss 8.280577317451192, train accuracy: 86.22%
Validation accuracy: 71.00%
Best Valid accuracy: 77.00%
Epoch 202, loss 9.380074425496101, train accuracy: 86.22%
Validation accuracy: 69.00%
Best Valid accuracy: 77.00%
Epoch 203, loss 8.325957510706544, train accuracy: 87.11%
Validation accuracy: 65.00%
Best Valid accuracy: 77.00%
Epoch 204, loss 8.613108882007722, train accuracy: 85.33%
Validation accuracy: 69.00%
Best Valid accuracy: 77.00%
Epoch 205, loss 8.972346532065243, train accuracy: 84.00%
Validation accuracy: 70.00%
Best Valid accuracy: 77.00%
Epoch 206, loss 8.118860409932104, train accuracy: 87.33%
Validation accuracy: 70.00%
Best Valid accuracy: 77.00%
Epoch 207, loss 7.982670848859052, train accuracy: 87.56%
Validation accuracy: 75.00%
Best Valid accuracy: 77.00%
Epoch 208, loss 7.802969352263401, train accuracy: 86.44%
Validation accuracy: 69.00%
Best Valid accuracy: 77.00%
Epoch 209, loss 8.340623431914313, train accuracy: 85.56%
Validation accuracy: 58.00%
Best Valid accuracy: 77.00%
Epoch 210, loss 7.847022052519047, train accuracy: 88.67%
Validation accuracy: 67.00%
Best Valid accuracy: 77.00%
Epoch 211, loss 7.177756237666613, train accuracy: 89.11%
Validation accuracy: 62.00%
Best Valid accuracy: 77.00%
Epoch 212, loss 7.6559069638855775, train accuracy: 88.67%
Validation accuracy: 72.00%
Best Valid accuracy: 77.00%
Epoch 213, loss 8.669404250069245, train accuracy: 86.00%
Validation accuracy: 64.00%
Best Valid accuracy: 77.00%
Epoch 214, loss 8.893161969696218, train accuracy: 84.44%
Validation accuracy: 71.00%
Best Valid accuracy: 77.00%
Epoch 215, loss 7.5023733096165985, train accuracy: 86.89%
Validation accuracy: 66.00%
Best Valid accuracy: 77.00%
Epoch 216, loss 9.002413713732066, train accuracy: 86.22%
Validation accuracy: 70.00%
Best Valid accuracy: 77.00%
Epoch 217, loss 8.6812167518905, train accuracy: 84.44%
Validation accuracy: 70.00%
Best Valid accuracy: 77.00%
Epoch 218, loss 6.255258480227065, train accuracy: 90.44%
Validation accuracy: 73.00%
Best Valid accuracy: 77.00%
Epoch 219, loss 8.722718899193277, train accuracy: 85.56%
Validation accuracy: 66.00%
Best Valid accuracy: 77.00%
Epoch 220, loss 9.049518635962736, train accuracy: 86.22%
Validation accuracy: 64.00%
Best Valid accuracy: 77.00%
Epoch 221, loss 7.544865698528781, train accuracy: 87.33%
Validation accuracy: 74.00%
Best Valid accuracy: 77.00%
Epoch 222, loss 8.154065423623065, train accuracy: 87.56%
Validation accuracy: 69.00%
Best Valid accuracy: 77.00%
Epoch 223, loss 7.930836172219621, train accuracy: 86.22%
Validation accuracy: 67.00%
Best Valid accuracy: 77.00%
Epoch 224, loss 9.399215850152517, train accuracy: 84.67%
Validation accuracy: 66.00%
Best Valid accuracy: 77.00%
Epoch 225, loss 10.256940205347286, train accuracy: 83.11%
Validation accuracy: 74.00%
Best Valid accuracy: 77.00%
Epoch 226, loss 9.064772231775223, train accuracy: 86.89%
Validation accuracy: 69.00%
Best Valid accuracy: 77.00%
Epoch 227, loss 8.503812542343969, train accuracy: 86.00%
Validation accuracy: 71.00%
Best Valid accuracy: 77.00%
Epoch 228, loss 7.61934057378657, train accuracy: 89.11%
Validation accuracy: 65.00%
Best Valid accuracy: 77.00%
Epoch 229, loss 8.708458783778058, train accuracy: 85.56%
Validation accuracy: 73.00%
Best Valid accuracy: 77.00%
Epoch 230, loss 6.92542603247756, train accuracy: 89.33%
Validation accuracy: 72.00%
Best Valid accuracy: 77.00%
Epoch 231, loss 8.294265814634352, train accuracy: 85.56%
Validation accuracy: 66.00%
Best Valid accuracy: 77.00%
Epoch 232, loss 7.942482697969559, train accuracy: 88.44%
Validation accuracy: 68.00%
Best Valid accuracy: 77.00%
Epoch 233, loss 8.692325480485243, train accuracy: 85.78%
Validation accuracy: 63.00%
Best Valid accuracy: 77.00%
Epoch 234, loss 8.203669733925265, train accuracy: 88.67%
Validation accuracy: 60.00%
Best Valid accuracy: 77.00%
Epoch 235, loss 8.0616257262118, train accuracy: 85.78%
Validation accuracy: 72.00%
Best Valid accuracy: 77.00%
Epoch 236, loss 8.685417215878577, train accuracy: 85.56%
Validation accuracy: 63.00%
Best Valid accuracy: 77.00%
Epoch 237, loss 8.353509405749799, train accuracy: 88.89%
Validation accuracy: 68.00%
Best Valid accuracy: 77.00%
Epoch 238, loss 7.381434294239874, train accuracy: 87.56%
Validation accuracy: 68.00%
Best Valid accuracy: 77.00%
Epoch 239, loss 8.279294239135664, train accuracy: 88.44%
Validation accuracy: 66.00%
Best Valid accuracy: 77.00%
Epoch 240, loss 8.887394211047114, train accuracy: 86.44%
Validation accuracy: 75.00%
Best Valid accuracy: 77.00%
Epoch 241, loss 7.25284259290201, train accuracy: 89.11%
Validation accuracy: 58.00%
Best Valid accuracy: 77.00%
Epoch 242, loss 8.131675163366529, train accuracy: 85.56%
Validation accuracy: 69.00%
Best Valid accuracy: 77.00%
Epoch 243, loss 8.794638884585156, train accuracy: 85.56%
Validation accuracy: 69.00%
Best Valid accuracy: 77.00%
Epoch 244, loss 7.859499611612772, train accuracy: 86.00%
Validation accuracy: 63.00%
Best Valid accuracy: 77.00%
Epoch 245, loss 8.77214518410654, train accuracy: 84.67%
Validation accuracy: 64.00%
Best Valid accuracy: 77.00%
Epoch 246, loss 8.549685249942348, train accuracy: 86.00%
Validation accuracy: 70.00%
Best Valid accuracy: 77.00%
Epoch 247, loss 8.75508074944869, train accuracy: 85.78%
Validation accuracy: 74.00%
Best Valid accuracy: 77.00%
Epoch 248, loss 6.872247920611365, train accuracy: 90.67%
Validation accuracy: 65.00%
Best Valid accuracy: 77.00%
Epoch 249, loss 9.492748403194417, train accuracy: 85.78%
Validation accuracy: 65.00%
Best Valid accuracy: 77.00%
Epoch 250, loss 7.45171126066499, train accuracy: 87.33%
Validation accuracy: 62.00%
Best Valid accuracy: 77.00%


```

### The other one 

``` 

Epoch 1 loss 2.2957641935661908 valid acc 2/16
Epoch 1 loss 11.527611239380313 valid acc 2/16
Epoch 1 loss 11.496252920809328 valid acc 2/16
Epoch 1 loss 11.444332071099431 valid acc 2/16
Epoch 1 loss 11.483366568513699 valid acc 2/16
Epoch 1 loss 11.334370406454351 valid acc 3/16
Epoch 1 loss 11.225966933447198 valid acc 3/16
Epoch 1 loss 11.119675155046451 valid acc 3/16
Epoch 1 loss 11.248558224501146 valid acc 6/16
Epoch 1 loss 10.63539593012353 valid acc 7/16
Epoch 1 loss 9.75679331757272 valid acc 6/16
Epoch 1 loss 8.842553851913465 valid acc 9/16
Epoch 1 loss 7.366943643128973 valid acc 12/16
Epoch 1 loss 6.698704736049108 valid acc 11/16
Epoch 1 loss 7.275132060063986 valid acc 11/16
Epoch 1 loss 7.61581344114081 valid acc 9/16
Epoch 1 loss 8.318292055924047 valid acc 11/16
Epoch 1 loss 6.595732120762623 valid acc 11/16
Epoch 1 loss 6.979315228996258 valid acc 13/16
Epoch 1 loss 5.3784703077781355 valid acc 10/16
Epoch 1 loss 5.300477006319586 valid acc 11/16
Epoch 1 loss 4.960677394647848 valid acc 13/16
Epoch 1 loss 3.4864888345003022 valid acc 12/16
Epoch 1 loss 5.450555843304258 valid acc 11/16
Epoch 1 loss 3.9382092722402273 valid acc 10/16
Epoch 1 loss 4.321721459080424 valid acc 9/16
Epoch 1 loss 9.591483024468321 valid acc 10/16
Epoch 1 loss 4.586240213435186 valid acc 13/16
Epoch 1 loss 5.337624614496185 valid acc 12/16
Epoch 1 loss 3.2904254129245443 valid acc 12/16
Epoch 1 loss 4.966844951540949 valid acc 12/16
Epoch 1 loss 3.9371715709640274 valid acc 12/16
Epoch 1 loss 4.035451376640495 valid acc 12/16
Epoch 1 loss 4.602274305652619 valid acc 14/16
Epoch 1 loss 6.193906429794228 valid acc 14/16
Epoch 1 loss 3.7640769536085386 valid acc 11/16
Epoch 1 loss 3.722755251993192 valid acc 12/16
Epoch 1 loss 3.4334070319234167 valid acc 12/16
Epoch 1 loss 4.564500418912546 valid acc 13/16
Epoch 1 loss 4.535252692161462 valid acc 12/16
Epoch 1 loss 4.39211094875854 valid acc 14/16
Epoch 1 loss 3.944033967687689 valid acc 15/16
Epoch 1 loss 3.8246239049925146 valid acc 15/16
Epoch 1 loss 3.0587497436889413 valid acc 15/16
Epoch 1 loss 4.385167702106479 valid acc 14/16
Epoch 1 loss 2.893339031895506 valid acc 14/16
Epoch 1 loss 3.656507875418993 valid acc 15/16
Epoch 1 loss 3.1779189487033417 valid acc 16/16
Epoch 1 loss 2.3666216002613627 valid acc 14/16
Epoch 1 loss 2.1521566063750233 valid acc 14/16
Epoch 1 loss 3.7013410205505863 valid acc 14/16
Epoch 1 loss 3.2191922702857925 valid acc 16/16
Epoch 1 loss 3.794380902902659 valid acc 14/16
Epoch 1 loss 3.162877278693033 valid acc 12/16
Epoch 1 loss 3.7753154936871693 valid acc 14/16
Epoch 1 loss 2.7586033148171025 valid acc 14/16
Epoch 1 loss 2.8258386632084846 valid acc 13/16
Epoch 1 loss 3.2505086640693195 valid acc 14/16
Epoch 1 loss 3.335280495589535 valid acc 15/16
Epoch 1 loss 3.3561253650286513 valid acc 14/16
Epoch 1 loss 2.96746621796128 valid acc 13/16
Epoch 1 loss 3.4735513342855087 valid acc 14/16
Epoch 1 loss 3.673541086897852 valid acc 14/16
Epoch 2 loss 0.45149386260248286 valid acc 15/16
Epoch 2 loss 3.3986624877363996 valid acc 14/16
Epoch 2 loss 3.459720568213158 valid acc 15/16
Epoch 2 loss 3.838803768089151 valid acc 15/16
Epoch 2 loss 2.9058636421531236 valid acc 15/16
Epoch 2 loss 2.2945141672776033 valid acc 15/16
Epoch 2 loss 2.364693828066602 valid acc 14/16
Epoch 2 loss 3.459740999864334 valid acc 15/16
Epoch 2 loss 2.790742447217223 valid acc 15/16
Epoch 2 loss 2.0927235451855872 valid acc 15/16
Epoch 2 loss 2.9195356443411917 valid acc 15/16
Epoch 2 loss 3.992251184683697 valid acc 15/16
Epoch 2 loss 2.8098551137583896 valid acc 15/16
Epoch 2 loss 3.649161653621068 valid acc 15/16
Epoch 2 loss 3.9590928113901853 valid acc 15/16
Epoch 2 loss 2.402061846271306 valid acc 14/16
Epoch 2 loss 3.9014991609609053 valid acc 14/16
Epoch 2 loss 2.97725308912715 valid acc 16/16
Epoch 2 loss 2.324423631040179 valid acc 15/16
Epoch 2 loss 1.9411409849407415 valid acc 15/16
Epoch 2 loss 2.920000478438989 valid acc 12/16
Epoch 2 loss 3.4166081770718395 valid acc 13/16
Epoch 2 loss 1.2269317249893354 valid acc 14/16
Epoch 2 loss 2.511081474545964 valid acc 15/16
Epoch 2 loss 1.86369121446696 valid acc 14/16
Epoch 2 loss 2.3450669472948924 valid acc 14/16
Epoch 2 loss 2.5324415493534205 valid acc 15/16
Epoch 2 loss 1.5303593233769113 valid acc 15/16
Epoch 2 loss 3.1190354784027554 valid acc 15/16
Epoch 2 loss 1.753622715815748 valid acc 15/16
Epoch 2 loss 2.4773555221644035 valid acc 14/16
Epoch 2 loss 2.305453618388124 valid acc 14/16
Epoch 2 loss 1.3915788607822244 valid acc 14/16
Epoch 2 loss 2.699725355886399 valid acc 15/16
Epoch 2 loss 3.595458431585712 valid acc 15/16
Epoch 2 loss 2.057884702557991 valid acc 15/16
Epoch 2 loss 1.6913396855695857 valid acc 14/16
Epoch 2 loss 2.2128067520814887 valid acc 13/16
Epoch 2 loss 2.1739475002285182 valid acc 16/16
Epoch 2 loss 2.2106606924076075 valid acc 15/16
Epoch 2 loss 1.59860600253556 valid acc 14/16
Epoch 2 loss 2.8733648632272484 valid acc 16/16
Epoch 2 loss 1.5888585232831507 valid acc 15/16
Epoch 2 loss 1.708173532487618 valid acc 14/16
Epoch 2 loss 2.248677137954422 valid acc 16/16
Epoch 2 loss 1.4571605698345884 valid acc 16/16
Epoch 2 loss 2.6523229708564338 valid acc 15/16
Epoch 2 loss 2.8623949874639822 valid acc 16/16
Epoch 2 loss 2.0110603122571673 valid acc 16/16
Epoch 2 loss 1.4285175107069332 valid acc 16/16
Epoch 2 loss 1.9511960892267777 valid acc 14/16
Epoch 2 loss 1.893527264422385 valid acc 15/16
Epoch 2 loss 2.516861889682067 valid acc 15/16
Epoch 2 loss 1.5574408528293484 valid acc 15/16
Epoch 2 loss 2.4618412003175507 valid acc 15/16
Epoch 2 loss 1.7402369478160957 valid acc 15/16
Epoch 2 loss 1.8476051625764114 valid acc 14/16
Epoch 2 loss 1.9852239601922903 valid acc 15/16
Epoch 2 loss 2.1064810278004753 valid acc 14/16
Epoch 2 loss 1.7151277522485984 valid acc 15/16
Epoch 2 loss 1.9231086672107816 valid acc 14/16
Epoch 2 loss 1.376445665419905 valid acc 15/16
Epoch 2 loss 2.335175010149534 valid acc 15/16
Epoch 3 loss 0.2317713110804014 valid acc 16/16
Epoch 3 loss 1.7265885913488765 valid acc 16/16
Epoch 3 loss 2.7109258822964053 valid acc 14/16
Epoch 3 loss 2.2960891497517535 valid acc 14/16
Epoch 3 loss 1.6837744863686954 valid acc 14/16
Epoch 3 loss 1.4111828615594457 valid acc 14/16
Epoch 3 loss 2.1902118298973314 valid acc 15/16
Epoch 3 loss 2.011731692610521 valid acc 15/16
Epoch 3 loss 2.009911479410221 valid acc 15/16
Epoch 3 loss 1.6682231739273938 valid acc 14/16
Epoch 3 loss 1.9923112854369025 valid acc 16/16
Epoch 3 loss 3.2304902745789357 valid acc 15/16
Epoch 3 loss 2.6003508097096715 valid acc 15/16
Epoch 3 loss 2.4126680247620316 valid acc 15/16
Epoch 3 loss 2.9338642556115695 valid acc 15/16
Epoch 3 loss 1.2696445575961894 valid acc 14/16
Epoch 3 loss 2.9630585282132498 valid acc 16/16
Epoch 3 loss 2.34477006057395 valid acc 15/16
Epoch 3 loss 2.176529036140377 valid acc 15/16
Epoch 3 loss 1.550841247980193 valid acc 16/16
Epoch 3 loss 1.5275542922949468 valid acc 14/16
Epoch 3 loss 1.346210033857008 valid acc 14/16
Epoch 3 loss 0.5781899661928422 valid acc 14/16
Epoch 3 loss 1.6843793149957578 valid acc 14/16
Epoch 3 loss 1.2059529292775801 valid acc 15/16
Epoch 3 loss 1.3827402405736455 valid acc 13/16
Epoch 3 loss 1.5798009698817705 valid acc 14/16
Epoch 3 loss 1.9202741428309107 valid acc 14/16
Epoch 3 loss 1.3296727521597371 valid acc 14/16
Epoch 3 loss 1.1062872227244966 valid acc 14/16
Epoch 3 loss 2.3452977550155185 valid acc 15/16
Epoch 3 loss 1.4346487401309584 valid acc 14/16
Epoch 3 loss 0.9746458151061429 valid acc 16/16
Epoch 3 loss 1.176039926740007 valid acc 15/16
Epoch 3 loss 2.5829900022839185 valid acc 16/16
Epoch 3 loss 1.808473733961999 valid acc 16/16
Epoch 3 loss 1.7475303294848863 valid acc 15/16
Epoch 3 loss 1.5414061898748521 valid acc 15/16
Epoch 3 loss 1.413818628404657 valid acc 16/16
Epoch 3 loss 1.7642392045109911 valid acc 16/16
Epoch 3 loss 0.8124947333811772 valid acc 16/16
Epoch 3 loss 2.077268684837174 valid acc 16/16
Epoch 3 loss 1.2224052968212549 valid acc 16/16
Epoch 3 loss 1.15676337192975 valid acc 16/16
Epoch 3 loss 1.7527703935290568 valid acc 16/16
Epoch 3 loss 1.014119010197679 valid acc 16/16
Epoch 3 loss 2.5242253693780063 valid acc 16/16
Epoch 3 loss 2.3488771345594817 valid acc 16/16
Epoch 3 loss 1.100530150521262 valid acc 16/16
Epoch 3 loss 1.4924375711240891 valid acc 16/16
Epoch 3 loss 1.0760497875147124 valid acc 16/16
Epoch 3 loss 1.238925392728147 valid acc 16/16
Epoch 3 loss 2.0812034821857988 valid acc 16/16
Epoch 3 loss 0.8762231895785462 valid acc 16/16
Epoch 3 loss 1.6736137018582227 valid acc 16/16
Epoch 3 loss 0.8341934167305216 valid acc 15/16
Epoch 3 loss 1.2145874558080882 valid acc 15/16
Epoch 3 loss 2.326293324366312 valid acc 14/16
Epoch 3 loss 1.7870934907074023 valid acc 15/16
Epoch 3 loss 1.7214437819803523 valid acc 15/16
Epoch 3 loss 1.8253261869523592 valid acc 16/16
Epoch 3 loss 1.57053274185395 valid acc 14/16
Epoch 3 loss 2.1232249095664946 valid acc 16/16
Epoch 4 loss 0.10915595859701469 valid acc 14/16
Epoch 4 loss 1.5582966104694034 valid acc 16/16
Epoch 4 loss 2.1796001743631797 valid acc 15/16
Epoch 4 loss 1.5307266412502742 valid acc 14/16
Epoch 4 loss 1.1207905140005425 valid acc 14/16
Epoch 4 loss 0.6227490212738729 valid acc 15/16
Epoch 4 loss 1.6761111600668044 valid acc 13/16
Epoch 4 loss 1.5660829773549179 valid acc 15/16
Epoch 4 loss 1.4967776562840198 valid acc 15/16
Epoch 4 loss 1.2688870788428834 valid acc 14/16
Epoch 4 loss 1.974425760162009 valid acc 15/16
Epoch 4 loss 2.0926600873811174 valid acc 15/16
Epoch 4 loss 2.6248590376956105 valid acc 15/16
Epoch 4 loss 1.5381717404156776 valid acc 16/16
Epoch 4 loss 2.3158822773653522 valid acc 16/16
Epoch 4 loss 1.1800144087740065 valid acc 13/16
Epoch 4 loss 2.232222476794722 valid acc 13/16
Epoch 4 loss 1.6401827518344525 valid acc 15/16
Epoch 4 loss 1.761608928096538 valid acc 16/16
Epoch 4 loss 1.4479785859851997 valid acc 15/16
Epoch 4 loss 1.5422127429722803 valid acc 14/16
Epoch 4 loss 1.2589016845713437 valid acc 15/16
Epoch 4 loss 0.48089682849764664 valid acc 15/16
Epoch 4 loss 1.634910858917919 valid acc 14/16
Epoch 4 loss 1.0342671091899285 valid acc 15/16
Epoch 4 loss 0.8716481902444475 valid acc 14/16
Epoch 4 loss 1.6728788552047416 valid acc 15/16
Epoch 4 loss 1.345961999503594 valid acc 15/16
Epoch 4 loss 1.0620916395074722 valid acc 15/16
Epoch 4 loss 0.8015294649137612 valid acc 14/16
Epoch 4 loss 0.8840844266627484 valid acc 15/16
Epoch 4 loss 1.1587109018621777 valid acc 13/16
Epoch 4 loss 0.978649552073666 valid acc 15/16
Epoch 4 loss 1.6632289999402405 valid acc 16/16
Epoch 4 loss 1.1810208400343618 valid acc 15/16
Epoch 4 loss 1.5867778719444114 valid acc 15/16
Epoch 4 loss 1.7051853133208046 valid acc 15/16
Epoch 4 loss 0.9361310785808075 valid acc 15/16
Epoch 4 loss 1.5466008307795085 valid acc 16/16
Epoch 4 loss 0.9296676296425447 valid acc 16/16
Epoch 4 loss 0.9974927784034628 valid acc 14/16
Epoch 4 loss 1.3304535734958316 valid acc 15/16
Epoch 4 loss 0.6409373839844599 valid acc 16/16
Epoch 4 loss 0.7822413006192678 valid acc 16/16
Epoch 4 loss 1.5586306870610651 valid acc 14/16
Epoch 4 loss 0.8007414348607208 valid acc 16/16
Epoch 4 loss 1.6517126306404637 valid acc 15/16
Epoch 4 loss 1.7401459605488485 valid acc 16/16
Epoch 4 loss 0.9387182218126852 valid acc 16/16
Epoch 4 loss 1.060445354667464 valid acc 16/16
Epoch 4 loss 0.7328871171505436 valid acc 15/16
Epoch 4 loss 0.6833505719224723 valid acc 16/16
Epoch 4 loss 1.5598425245326217 valid acc 15/16
Epoch 4 loss 0.8088080571610269 valid acc 16/16
Epoch 4 loss 1.5352033517300268 valid acc 16/16
Epoch 4 loss 0.5118554441074823 valid acc 16/16
Epoch 4 loss 1.100609094693729 valid acc 16/16
Epoch 4 loss 1.0957333563806322 valid acc 16/16
Epoch 4 loss 1.348049269015641 valid acc 16/16
Epoch 4 loss 1.591332069979978 valid acc 16/16
Epoch 4 loss 1.1721483454966255 valid acc 16/16
Epoch 4 loss 1.0244016872314519 valid acc 16/16
Epoch 4 loss 1.8876975624070487 valid acc 14/16
Epoch 5 loss 0.03234345203395622 valid acc 16/16
Epoch 5 loss 0.9693321272230602 valid acc 16/16
Epoch 5 loss 1.265417684069551 valid acc 15/16
Epoch 5 loss 1.236490667683578 valid acc 15/16
Epoch 5 loss 1.170864547549977 valid acc 15/16
Epoch 5 loss 0.8931140720023362 valid acc 16/16
Epoch 5 loss 1.203199353176616 valid acc 15/16
Epoch 5 loss 1.3912396260894302 valid acc 16/16
Epoch 5 loss 1.324460668285742 valid acc 15/16
Epoch 5 loss 0.5500271284447033 valid acc 16/16
Epoch 5 loss 1.696505511197456 valid acc 16/16
Epoch 5 loss 2.2802324220342287 valid acc 16/16
Epoch 5 loss 2.2083526788445207 valid acc 16/16
Epoch 5 loss 0.7286295143212148 valid acc 16/16
Epoch 5 loss 1.7376567150014588 valid acc 16/16
Epoch 5 loss 0.503074202430853 valid acc 15/16
Epoch 5 loss 2.1751378542189994 valid acc 16/16
Epoch 5 loss 1.4478154545409176 valid acc 16/16
Epoch 5 loss 1.6884657292061291 valid acc 16/16
Epoch 5 loss 0.8875664919534026 valid acc 16/16
Epoch 5 loss 1.221264292963046 valid acc 14/16
Epoch 5 loss 0.9493092117440709 valid acc 15/16
Epoch 5 loss 0.5332379727959633 valid acc 14/16
Epoch 5 loss 0.9792123860497504 valid acc 15/16
Epoch 5 loss 0.8567743880168875 valid acc 14/16
Epoch 5 loss 1.0408295161169876 valid acc 15/16
Epoch 5 loss 0.794338297399632 valid acc 16/16
Epoch 5 loss 1.1414990495112174 valid acc 16/16
Epoch 5 loss 1.040180598820655 valid acc 14/16
Epoch 5 loss 0.875698434779563 valid acc 15/16
Epoch 5 loss 1.2639845522678514 valid acc 15/16
Epoch 5 loss 1.1500297785047413 valid acc 14/16
Epoch 5 loss 0.48637622033223 valid acc 15/16
Epoch 5 loss 0.9291015863865904 valid acc 14/16
Epoch 5 loss 1.5722590497367093 valid acc 14/16
Epoch 5 loss 0.7630371102050661 valid acc 15/16
Epoch 5 loss 1.0469842947530632 valid acc 16/16
Epoch 5 loss 0.9048975848065046 valid acc 16/16
Epoch 5 loss 1.4549670118042777 valid acc 15/16
Epoch 5 loss 0.82093201008181 valid acc 16/16
Epoch 5 loss 0.5569914688895852 valid acc 16/16
Epoch 5 loss 0.9626239970044703 valid acc 16/16
Epoch 5 loss 0.758021836277261 valid acc 16/16
Epoch 5 loss 0.319079705540347 valid acc 14/16
Epoch 5 loss 1.6341944520251184 valid acc 15/16
Epoch 5 loss 0.638145783017557 valid acc 15/16
Epoch 5 loss 0.8016392934741132 valid acc 15/16
Epoch 5 loss 1.3894104770307933 valid acc 16/16
Epoch 5 loss 0.38642791421091116 valid acc 14/16
Epoch 5 loss 0.9497702083658156 valid acc 14/16
Epoch 5 loss 1.7442700353041325 valid acc 15/16
Epoch 5 loss 1.035655132483441 valid acc 15/16
Epoch 5 loss 1.2096397856341148 valid acc 16/16
Epoch 5 loss 0.9254740001633956 valid acc 16/16
Epoch 5 loss 1.0806692647914935 valid acc 16/16
Epoch 5 loss 0.3346736728294448 valid acc 16/16
Epoch 5 loss 0.5750636626155301 valid acc 15/16
Epoch 5 loss 0.9553388630512938 valid acc 15/16
Epoch 5 loss 1.2154764805937448 valid acc 16/16
Epoch 5 loss 1.1524029421814463 valid acc 16/16
Epoch 5 loss 0.776720852615334 valid acc 15/16
Epoch 5 loss 0.5318560444992817 valid acc 15/16
Epoch 5 loss 0.9984093264974029 valid acc 15/16
Epoch 6 loss 0.0365205730988325 valid acc 16/16
Epoch 6 loss 0.9097471434321944 valid acc 16/16
Epoch 6 loss 1.7274787543839931 valid acc 15/16
Epoch 6 loss 0.787324260277778 valid acc 15/16
Epoch 6 loss 0.8672883076507796 valid acc 14/16
Epoch 6 loss 0.8390725519144695 valid acc 16/16
Epoch 6 loss 0.7933960448081648 valid acc 14/16
Epoch 6 loss 1.1360993523855565 valid acc 16/16
Epoch 6 loss 1.118577359646686 valid acc 14/16
Epoch 6 loss 0.9932235948811059 valid acc 16/16
Epoch 6 loss 1.2576832610608502 valid acc 15/16
Epoch 6 loss 1.4714894534414442 valid acc 16/16
Epoch 6 loss 1.7941588201383187 valid acc 16/16
Epoch 6 loss 1.5477887238835253 valid acc 16/16
Epoch 6 loss 1.4927807580641579 valid acc 16/16
Epoch 6 loss 0.8898037762316613 valid acc 15/16
Epoch 6 loss 2.1599899317099567 valid acc 15/16
Epoch 6 loss 1.1705548211894894 valid acc 15/16
Epoch 6 loss 1.3938174725123023 valid acc 16/16
Epoch 6 loss 0.6189056184916373 valid acc 16/16
Epoch 6 loss 1.4270865086272804 valid acc 14/16
Epoch 6 loss 0.8850166015377283 valid acc 15/16
Epoch 6 loss 0.7376056678300837 valid acc 16/16
Epoch 6 loss 0.9398289403973357 valid acc 15/16
Epoch 6 loss 0.8707716219953843 valid acc 15/16
Epoch 6 loss 0.6814852095442268 valid acc 15/16
Epoch 6 loss 0.6521613767401626 valid acc 15/16
Epoch 6 loss 0.898378337644113 valid acc 16/16
Epoch 6 loss 1.091811718476087 valid acc 15/16
Epoch 6 loss 0.3165128692433715 valid acc 15/16
Epoch 6 loss 0.40669293075731494 valid acc 16/16
Epoch 6 loss 0.9753284064427009 valid acc 15/16
Epoch 6 loss 0.19577497350842685 valid acc 15/16
Epoch 6 loss 1.0402356077467703 valid acc 15/16
Epoch 6 loss 1.424445664695252 valid acc 15/16
Epoch 6 loss 0.8394594852417427 valid acc 16/16
Epoch 6 loss 1.2010742775353995 valid acc 13/16
Epoch 6 loss 0.6837515253169462 valid acc 15/16
Epoch 6 loss 1.0760613590572423 valid acc 14/16
Epoch 6 loss 1.1565846491251854 valid acc 15/16
Epoch 6 loss 0.3610014363733528 valid acc 15/16
Epoch 6 loss 0.7453130744297689 valid acc 15/16
Epoch 6 loss 0.7077086118510572 valid acc 16/16
Epoch 6 loss 0.5130051260376296 valid acc 14/16
Epoch 6 loss 0.8867236315129007 valid acc 15/16
Epoch 6 loss 0.347094061948593 valid acc 16/16
Epoch 6 loss 1.0929257627206692 valid acc 16/16
Epoch 6 loss 1.576930449397246 valid acc 16/16
Epoch 6 loss 0.7854271222408996 valid acc 16/16
Epoch 6 loss 0.32527879368993073 valid acc 16/16
Epoch 6 loss 0.46475257590518043 valid acc 16/16
Epoch 6 loss 0.6357171455008641 valid acc 16/16
Epoch 6 loss 1.0184254757671924 valid acc 16/16
Epoch 6 loss 0.2992307758484931 valid acc 16/16
Epoch 6 loss 1.3763093043959762 valid acc 16/16
Epoch 6 loss 0.5230424646029812 valid acc 14/16
Epoch 6 loss 0.7675453309589693 valid acc 15/16
Epoch 6 loss 0.4837832195541094 valid acc 15/16
Epoch 6 loss 0.73592738548936 valid acc 16/16
Epoch 6 loss 0.9803625861885262 valid acc 15/16
Epoch 6 loss 0.4389437251066503 valid acc 15/16
Epoch 6 loss 0.638266005402379 valid acc 14/16
Epoch 6 loss 0.8769865187897664 valid acc 15/16
Epoch 7 loss 0.014407553819562158 valid acc 15/16
Epoch 7 loss 0.9462257266866028 valid acc 15/16
Epoch 7 loss 1.431713110670983 valid acc 16/16
Epoch 7 loss 0.874975557472722 valid acc 15/16
Epoch 7 loss 0.6427258595497077 valid acc 15/16
Epoch 7 loss 0.6742801841539647 valid acc 16/16
Epoch 7 loss 1.4676665847899386 valid acc 15/16
Epoch 7 loss 0.7785754157829231 valid acc 15/16
Epoch 7 loss 1.3034275278296015 valid acc 16/16
Epoch 7 loss 0.29059721390351284 valid acc 15/16
Epoch 7 loss 0.6569341419023238 valid acc 15/16
Epoch 7 loss 1.4999461757019006 valid acc 15/16
Epoch 7 loss 1.4868930200964352 valid acc 15/16
Epoch 7 loss 1.0757854422708828 valid acc 15/16
Epoch 7 loss 0.9555273679158534 valid acc 15/16
Epoch 7 loss 0.5291199161783386 valid acc 15/16
Epoch 7 loss 2.2136113336168832 valid acc 16/16
Epoch 7 loss 0.9004877505540572 valid acc 15/16
Epoch 7 loss 0.9428043124587031 valid acc 15/16
Epoch 7 loss 0.8016836189543343 valid acc 15/16
Epoch 7 loss 1.1076616651540658 valid acc 14/16
Epoch 7 loss 0.6778087910976951 valid acc 14/16
Epoch 7 loss 0.6830764235620281 valid acc 15/16
Epoch 7 loss 0.6882623727877739 valid acc 14/16
Epoch 7 loss 1.0759694904324824 valid acc 16/16
Epoch 7 loss 0.8749612361685228 valid acc 15/16
Epoch 7 loss 0.9137788150323898 valid acc 15/16
Epoch 7 loss 0.7433515213263442 valid acc 15/16
Epoch 7 loss 0.543911339414473 valid acc 16/16
Epoch 7 loss 0.2521160420765863 valid acc 16/16
Epoch 7 loss 1.2368711272308328 valid acc 16/16
Epoch 7 loss 0.7641117971951528 valid acc 16/16
Epoch 7 loss 0.7981483147319148 valid acc 16/16
Epoch 7 loss 0.42133563544589386 valid acc 16/16
Epoch 7 loss 1.3161874746316995 valid acc 16/16
Epoch 7 loss 0.7702677808727634 valid acc 16/16
Epoch 7 loss 0.9249174648563123 valid acc 15/16
Epoch 7 loss 0.6182079402944944 valid acc 15/16
Epoch 7 loss 0.6282519981362599 valid acc 15/16
Epoch 7 loss 1.231340779590987 valid acc 15/16
Epoch 7 loss 0.41043000461646884 valid acc 15/16
Epoch 7 loss 0.7912698562521563 valid acc 15/16
Epoch 7 loss 0.8746843098600843 valid acc 15/16
Epoch 7 loss 0.23173513027351464 valid acc 15/16
Epoch 7 loss 1.0827471657130616 valid acc 15/16
Epoch 7 loss 0.2557972589378684 valid acc 15/16
Epoch 7 loss 0.8904480630852961 valid acc 16/16
Epoch 7 loss 1.5010506682056273 valid acc 16/16
Epoch 7 loss 0.6879083288835657 valid acc 16/16
Epoch 7 loss 0.8128043185883683 valid acc 15/16
Epoch 7 loss 0.6254470061704231 valid acc 16/16
Epoch 7 loss 0.85580886031365 valid acc 15/16
Epoch 7 loss 0.8958343471905388 valid acc 16/16
Epoch 7 loss 0.45188163873473775 valid acc 16/16
Epoch 7 loss 0.8867512420485489 valid acc 14/16
Epoch 7 loss 0.2415059000562255 valid acc 16/16
Epoch 7 loss 0.9867899904707309 valid acc 16/16
Epoch 7 loss 0.4189928340002353 valid acc 16/16
Epoch 7 loss 0.9642965105035481 valid acc 14/16
Epoch 7 loss 0.6964830069961992 valid acc 15/16
Epoch 7 loss 1.2255730846552182 valid acc 16/16
Epoch 7 loss 0.671129281589774 valid acc 16/16
Epoch 7 loss 0.8875000670634768 valid acc 14/16
Epoch 8 loss 0.03626080684037153 valid acc 16/16
Epoch 8 loss 0.981147610669681 valid acc 16/16
Epoch 8 loss 1.6391743167299935 valid acc 16/16
Epoch 8 loss 0.4907637552932888 valid acc 16/16
Epoch 8 loss 0.2941219245185435 valid acc 15/16
Epoch 8 loss 0.5864114660613995 valid acc 16/16
Epoch 8 loss 0.8454241834864803 valid acc 14/16
Epoch 8 loss 0.9450308189091221 valid acc 14/16
Epoch 8 loss 0.5731004320258584 valid acc 15/16
Epoch 8 loss 0.4290021649681451 valid acc 14/16
Epoch 8 loss 0.764125010519638 valid acc 15/16
Epoch 8 loss 1.7432354609350669 valid acc 15/16
Epoch 8 loss 1.203111438130881 valid acc 15/16
Epoch 8 loss 0.895457701681687 valid acc 14/16
Epoch 8 loss 1.2325189146789717 valid acc 16/16
Epoch 8 loss 0.8138568728772526 valid acc 15/16
Epoch 8 loss 1.0985132783965854 valid acc 15/16
Epoch 8 loss 0.968183309997834 valid acc 16/16
Epoch 8 loss 0.6775006165195568 valid acc 16/16
Epoch 8 loss 0.5462509660479181 valid acc 16/16
Epoch 8 loss 1.0611984117050544 valid acc 15/16
Epoch 8 loss 0.579262456154518 valid acc 16/16
Epoch 8 loss 0.18622458920555252 valid acc 16/16
Epoch 8 loss 0.29395223948150323 valid acc 16/16
Epoch 8 loss 0.5364647382845344 valid acc 16/16
Epoch 8 loss 0.5737954378604342 valid acc 16/16
Epoch 8 loss 0.39729246913493976 valid acc 15/16
Epoch 8 loss 0.9576004541671963 valid acc 15/16
Epoch 8 loss 0.48070014040633424 valid acc 15/16
Epoch 8 loss 0.08622439462502215 valid acc 15/16
Epoch 8 loss 1.409597118837448 valid acc 15/16
Epoch 8 loss 0.7053736303118299 valid acc 15/16
Epoch 8 loss 0.25271908876438653 valid acc 15/16
Epoch 8 loss 0.43783717585477777 valid acc 16/16
Epoch 8 loss 1.450826010677448 valid acc 15/16
Epoch 8 loss 0.8120359437871107 valid acc 16/16
Epoch 8 loss 0.5768152133545903 valid acc 16/16
Epoch 8 loss 0.40612829301111086 valid acc 16/16
Epoch 8 loss 0.5867805229287715 valid acc 15/16
Epoch 8 loss 0.4772659598680998 valid acc 16/16
Epoch 8 loss 0.3585601242827176 valid acc 16/16
Epoch 8 loss 0.6223472340149515 valid acc 16/16
Epoch 8 loss 0.5151709504132189 valid acc 16/16
Epoch 8 loss 0.20859876578787523 valid acc 16/16
Epoch 8 loss 0.4282840273032941 valid acc 15/16
Epoch 8 loss 0.25773404799940003 valid acc 16/16
Epoch 8 loss 0.8919169166380333 valid acc 16/16
Epoch 8 loss 0.8288942983085483 valid acc 16/16
Epoch 8 loss 1.035188503138071 valid acc 16/16
Epoch 8 loss 0.4341047754609728 valid acc 16/16
Epoch 8 loss 0.6431624614407276 valid acc 16/16
Epoch 8 loss 0.8140173671449651 valid acc 16/16
Epoch 8 loss 0.7556760338542843 valid acc 16/16
Epoch 8 loss 0.2954345877817799 valid acc 15/16
Epoch 8 loss 0.6348964726789108 valid acc 16/16
Epoch 8 loss 0.31219585157855306 valid acc 16/16
Epoch 8 loss 0.4646882541032239 valid acc 15/16
Epoch 8 loss 0.5420220538245585 valid acc 15/16
Epoch 8 loss 0.7122574303467545 valid acc 15/16
Epoch 8 loss 0.6364236709273774 valid acc 13/16
Epoch 8 loss 0.9569512778787577 valid acc 14/16
Epoch 8 loss 0.42237426473233364 valid acc 14/16
Epoch 8 loss 0.37767096980208364 valid acc 15/16
Epoch 9 loss 0.08251956042145808 valid acc 15/16
Epoch 9 loss 1.238930484526596 valid acc 16/16
Epoch 9 loss 0.7179926319270218 valid acc 16/16
Epoch 9 loss 0.42701028905361715 valid acc 15/16
Epoch 9 loss 0.8128333085799209 valid acc 15/16
Epoch 9 loss 0.36528719216833894 valid acc 15/16
Epoch 9 loss 0.9739636451874265 valid acc 15/16
Epoch 9 loss 0.8280489693507491 valid acc 15/16
Epoch 9 loss 1.100988199511289 valid acc 15/16
Epoch 9 loss 0.4121594073277725 valid acc 14/16
Epoch 9 loss 0.8511858071335696 valid acc 15/16
Epoch 9 loss 0.7322174595219255 valid acc 15/16
Epoch 9 loss 1.2644498574137153 valid acc 15/16
Epoch 9 loss 0.8134486517980197 valid acc 15/16
Epoch 9 loss 1.341197626852357 valid acc 15/16
Epoch 9 loss 0.3044974048844523 valid acc 15/16
Epoch 9 loss 2.0023577147016596 valid acc 15/16
Epoch 9 loss 1.2471034373955918 valid acc 15/16
Epoch 9 loss 0.9079551759022172 valid acc 15/16
Epoch 9 loss 0.40059361694061396 valid acc 15/16
Epoch 9 loss 1.0229396444702834 valid acc 15/16
Epoch 9 loss 0.20574482708581257 valid acc 15/16
Epoch 9 loss 0.397847281666867 valid acc 13/16
Epoch 9 loss 0.7200750952978531 valid acc 14/16
Epoch 9 loss 0.44205876686530515 valid acc 14/16
Epoch 9 loss 0.694478872437649 valid acc 14/16
Epoch 9 loss 0.4016274615032617 valid acc 14/16
Epoch 9 loss 0.49048739102836414 valid acc 14/16
Epoch 9 loss 0.6331757007619182 valid acc 14/16
Epoch 9 loss 0.1874035573116267 valid acc 14/16
Epoch 9 loss 0.25259333502424963 valid acc 14/16
Epoch 9 loss 0.23292706235897387 valid acc 13/16
Epoch 9 loss 0.23391625435535407 valid acc 15/16
Epoch 9 loss 0.586942068866208 valid acc 15/16
Epoch 9 loss 0.9204107887092057 valid acc 14/16
Epoch 9 loss 0.4975591588117696 valid acc 14/16
Epoch 9 loss 0.7329494961547578 valid acc 15/16
Epoch 9 loss 0.235627295273534 valid acc 15/16
Epoch 9 loss 0.3847622309574319 valid acc 16/16
Epoch 9 loss 0.7479461346443977 valid acc 16/16
Epoch 9 loss 0.18000792043705766 valid acc 16/16
Epoch 9 loss 0.8393064418641798 valid acc 16/16
Epoch 9 loss 0.1278150730770084 valid acc 16/16
Epoch 9 loss 0.5293295544359324 valid acc 15/16
Epoch 9 loss 0.7831599831541654 valid acc 16/16
Epoch 9 loss 0.43715207612679685 valid acc 16/16
Epoch 9 loss 0.44709124164071906 valid acc 15/16
Epoch 9 loss 1.1535143094221447 valid acc 16/16
Epoch 9 loss 0.15168146892762044 valid acc 16/16
Epoch 9 loss 0.4684411543186523 valid acc 16/16
Epoch 9 loss 0.5183152807045026 valid acc 16/16
Epoch 9 loss 0.591862252656556 valid acc 16/16
Epoch 9 loss 0.5898252446799234 valid acc 16/16
Epoch 9 loss 0.5322239114828435 valid acc 16/16
Epoch 9 loss 1.2947430847520836 valid acc 15/16
Epoch 9 loss 0.33377944173955215 valid acc 15/16
Epoch 9 loss 0.7544658200257165 valid acc 15/16
Epoch 9 loss 0.33532070035516165 valid acc 16/16
Epoch 9 loss 0.6389044676370068 valid acc 15/16
Epoch 9 loss 0.46128102814458094 valid acc 16/16
Epoch 9 loss 0.4583262496737858 valid acc 15/16
Epoch 9 loss 0.41619695032458437 valid acc 15/16
Epoch 9 loss 0.38036658509234533 valid acc 16/16
Epoch 10 loss 0.015415949430915066 valid acc 15/16
Epoch 10 loss 0.8087208313826486 valid acc 16/16
Epoch 10 loss 0.78135396393404 valid acc 16/16
Epoch 10 loss 0.766187737538734 valid acc 16/16
Epoch 10 loss 0.6054138882130402 valid acc 15/16
Epoch 10 loss 0.2951437495429872 valid acc 15/16
Epoch 10 loss 0.8713640535505134 valid acc 15/16
Epoch 10 loss 0.7329651060844499 valid acc 15/16
Epoch 10 loss 0.5240246884854477 valid acc 15/16
Epoch 10 loss 0.7244989642285924 valid acc 14/16
Epoch 10 loss 0.7492481343232572 valid acc 14/16
Epoch 10 loss 1.3427959263757832 valid acc 15/16
Epoch 10 loss 1.206057774477763 valid acc 15/16
Epoch 10 loss 0.8741447827817193 valid acc 15/16
Epoch 10 loss 0.6002473581477403 valid acc 15/16
Epoch 10 loss 0.5459874377213744 valid acc 15/16
Epoch 10 loss 1.9212957745544907 valid acc 15/16
Epoch 10 loss 0.8558881316006504 valid acc 15/16
Epoch 10 loss 0.46784444859055774 valid acc 14/16
Epoch 10 loss 0.7819475202401249 valid acc 14/16
Epoch 10 loss 0.9598565328666341 valid acc 13/16
Epoch 10 loss 0.6430053382930447 valid acc 14/16
Epoch 10 loss 0.5246541439065731 valid acc 14/16
Epoch 10 loss 0.5662168440603825 valid acc 14/16
Epoch 10 loss 0.2394413316145752 valid acc 14/16
Epoch 10 loss 0.4339461352681258 valid acc 14/16
Epoch 10 loss 0.5591000349747298 valid acc 15/16
Epoch 10 loss 0.2863402488562846 valid acc 15/16
Epoch 10 loss 0.533402421835675 valid acc 14/16
Epoch 10 loss 0.0980082738540912 valid acc 14/16
Epoch 10 loss 0.46404599769128235 valid acc 14/16
Epoch 10 loss 0.5471614052826551 valid acc 14/16
Epoch 10 loss 0.4268577203634627 valid acc 15/16
Epoch 10 loss 0.29107230542189777 valid acc 16/16
Epoch 10 loss 0.9745630657635405 valid acc 16/16
Epoch 10 loss 0.5676181416474801 valid acc 16/16
Epoch 10 loss 0.16661122754481467 valid acc 16/16
Epoch 10 loss 0.37786458553696634 valid acc 16/16
Epoch 10 loss 0.6678731688804564 valid acc 16/16
Epoch 10 loss 0.35745259857822637 valid acc 16/16
Epoch 10 loss 0.22424199479128756 valid acc 16/16
Epoch 10 loss 0.21001214046935934 valid acc 16/16
Epoch 10 loss 0.18955275146346512 valid acc 16/16
Epoch 10 loss 0.5517153753303388 valid acc 15/16
Epoch 10 loss 0.6282757678389718 valid acc 15/16
Epoch 10 loss 0.1902410028585127 valid acc 16/16
Epoch 10 loss 0.6041217367259406 valid acc 16/16
Epoch 10 loss 0.5768629503221911 valid acc 16/16
Epoch 10 loss 1.1064874008319903 valid acc 15/16
Epoch 10 loss 0.3858517417078883 valid acc 16/16
Epoch 10 loss 0.5322085439651427 valid acc 15/16
Epoch 10 loss 0.6743118707247989 valid acc 16/16
Epoch 10 loss 0.8591965094139702 valid acc 16/16
Epoch 10 loss 0.24429609468492383 valid acc 16/16
Epoch 10 loss 0.4420522121530862 valid acc 16/16
Epoch 10 loss 0.20000908817339413 valid acc 16/16
Epoch 10 loss 0.6604210579123896 valid acc 16/16
Epoch 10 loss 0.5840790680104446 valid acc 15/16
Epoch 10 loss 0.8554629700035314 valid acc 15/16
Epoch 10 loss 0.8161896372485157 valid acc 15/16
Epoch 10 loss 0.37482498851961693 valid acc 16/16
Epoch 10 loss 0.5266782127052178 valid acc 16/16
Epoch 10 loss 0.9758319378825435 valid acc 15/16
Epoch 11 loss 0.0033032586138345144 valid acc 16/16
Epoch 11 loss 0.7587567034002326 valid acc 15/16
Epoch 11 loss 0.7716016722083039 valid acc 16/16
Epoch 11 loss 0.30424986272946875 valid acc 16/16
Epoch 11 loss 0.16106510635237448 valid acc 15/16
Epoch 11 loss 0.20882352510139945 valid acc 15/16
Epoch 11 loss 0.7736629891259623 valid acc 14/16
Epoch 11 loss 1.1466969456238187 valid acc 16/16
Epoch 11 loss 0.4939374837493066 valid acc 15/16
Epoch 11 loss 0.49154235625551296 valid acc 16/16
Epoch 11 loss 0.7603502939600131 valid acc 16/16
Epoch 11 loss 0.35157647392593194 valid acc 16/16
Epoch 11 loss 0.9471806369912044 valid acc 15/16
Epoch 11 loss 0.6907857394007798 valid acc 16/16
Epoch 11 loss 1.2810831995018876 valid acc 16/16
Epoch 11 loss 0.6086414817015662 valid acc 15/16
Epoch 11 loss 1.5727136902320566 valid acc 15/16
Epoch 11 loss 0.871657109550513 valid acc 16/16
Epoch 11 loss 0.9848568804592407 valid acc 16/16
Epoch 11 loss 0.45743832325835954 valid acc 16/16
Epoch 11 loss 0.9455123156921539 valid acc 16/16
Epoch 11 loss 0.46661821073838666 valid acc 16/16
Epoch 11 loss 0.24018858044805058 valid acc 15/16
Epoch 11 loss 0.17267480453452744 valid acc 16/16
Epoch 11 loss 0.490676258960859 valid acc 15/16
Epoch 11 loss 0.6087267302551 valid acc 15/16
Epoch 11 loss 0.317965360119836 valid acc 15/16
Epoch 11 loss 0.7376415352876999 valid acc 15/16
Epoch 11 loss 0.45158349350350346 valid acc 15/16
Epoch 11 loss 0.277516915098053 valid acc 15/16
Epoch 11 loss 0.7106322066565991 valid acc 15/16
Epoch 11 loss 0.3840683637568002 valid acc 16/16
Epoch 11 loss 0.1634975236220144 valid acc 15/16
Epoch 11 loss 0.9123237596894533 valid acc 15/16
Epoch 11 loss 0.8304839375602922 valid acc 15/16
Epoch 11 loss 0.4294332910499854 valid acc 15/16
Epoch 11 loss 0.5844043746145597 valid acc 16/16
Epoch 11 loss 0.2977249832946929 valid acc 16/16
Epoch 11 loss 0.5495237958453805 valid acc 16/16
Epoch 11 loss 0.5983118500228256 valid acc 16/16
Epoch 11 loss 0.3924771383334281 valid acc 16/16
Epoch 11 loss 0.4531389140155283 valid acc 16/16
Epoch 11 loss 0.17171227518704504 valid acc 16/16
Epoch 11 loss 0.2527475152851693 valid acc 16/16
Epoch 11 loss 0.24915468697511842 valid acc 16/16
Epoch 11 loss 0.11629585547326404 valid acc 16/16
Epoch 11 loss 0.6018375578105477 valid acc 16/16
Epoch 11 loss 0.28577345974073315 valid acc 16/16
Epoch 11 loss 0.18705532548493653 valid acc 16/16
Epoch 11 loss 0.7144887938720696 valid acc 16/16
Epoch 11 loss 0.4200779693888581 valid acc 16/16
Epoch 11 loss 0.3446592324363452 valid acc 15/16
Epoch 11 loss 0.5724373702511889 valid acc 15/16
Epoch 11 loss 0.16192999047210938 valid acc 15/16
Epoch 11 loss 0.2861050718005696 valid acc 15/16
Epoch 11 loss 0.13024698713426208 valid acc 15/16
Epoch 11 loss 0.9231632029460195 valid acc 15/16
Epoch 11 loss 0.9457804254242943 valid acc 15/16
Epoch 11 loss 0.6432350569925043 valid acc 15/16
Epoch 11 loss 0.30874427390824966 valid acc 15/16
Epoch 11 loss 0.4759352037492975 valid acc 16/16
Epoch 11 loss 0.46300871040930003 valid acc 15/16
Epoch 11 loss 0.4996138670245332 valid acc 15/16
Epoch 12 loss 0.0044500617764425265 valid acc 15/16
Epoch 12 loss 1.2238424748104721 valid acc 15/16
Epoch 12 loss 0.49304918086563937 valid acc 14/16
Epoch 12 loss 0.3692276010893179 valid acc 14/16
Epoch 12 loss 0.4885327269490499 valid acc 15/16
Epoch 12 loss 0.5795312587775949 valid acc 16/16
Epoch 12 loss 0.5117586336712883 valid acc 15/16
Epoch 12 loss 0.6632065712782015 valid acc 14/16
Epoch 12 loss 0.3654345322182039 valid acc 15/16
Epoch 12 loss 0.43784646528633736 valid acc 15/16
Epoch 12 loss 0.3018764179370985 valid acc 15/16
Epoch 12 loss 0.8455707450515213 valid acc 15/16
Epoch 12 loss 1.0175440719042235 valid acc 15/16
Epoch 12 loss 1.171290778410069 valid acc 16/16
Epoch 12 loss 0.5087491115807911 valid acc 16/16
Epoch 12 loss 0.4628125051016624 valid acc 15/16
Epoch 12 loss 0.8730837627524491 valid acc 16/16
Epoch 12 loss 0.4880679812231293 valid acc 16/16
Epoch 12 loss 0.4389804411094762 valid acc 15/16
Epoch 12 loss 0.540036822686248 valid acc 15/16
Epoch 12 loss 0.9641275209873184 valid acc 14/16
Epoch 12 loss 0.23774163015930092 valid acc 14/16
Epoch 12 loss 0.4885757612979532 valid acc 15/16
Epoch 12 loss 0.22127464119689333 valid acc 15/16
Epoch 12 loss 0.5522145929094993 valid acc 15/16
Epoch 12 loss 0.4091857112655138 valid acc 15/16
Epoch 12 loss 0.2828956311841859 valid acc 15/16
Epoch 12 loss 0.40770474555017255 valid acc 15/16
Epoch 12 loss 0.3297828230546698 valid acc 15/16
Epoch 12 loss 0.15851747665283242 valid acc 15/16
Epoch 12 loss 0.3020955554479876 valid acc 15/16
Epoch 12 loss 0.18651076947228218 valid acc 15/16
Epoch 12 loss 0.38095652404429015 valid acc 16/16
Epoch 12 loss 0.6369571478085421 valid acc 16/16
Epoch 12 loss 1.2758280727878288 valid acc 15/16
Epoch 12 loss 0.512378997518661 valid acc 16/16
Epoch 12 loss 0.387368060353283 valid acc 16/16
Epoch 12 loss 0.09478307113361623 valid acc 16/16
Epoch 12 loss 0.9892774736045197 valid acc 16/16
Epoch 12 loss 0.2158197514035957 valid acc 16/16
Epoch 12 loss 0.1815558116399698 valid acc 15/16
Epoch 12 loss 0.39997453372736824 valid acc 15/16
Epoch 12 loss 0.44194520173352125 valid acc 14/16
Epoch 12 loss 0.3459101640826716 valid acc 15/16
Epoch 12 loss 0.3552303994218433 valid acc 15/16
Epoch 12 loss 0.1122440883364092 valid acc 16/16
Epoch 12 loss 0.5322017733009846 valid acc 15/16
Epoch 12 loss 1.376845016050511 valid acc 16/16
Epoch 12 loss 0.7077238428082719 valid acc 16/16
Epoch 12 loss 0.25048638599108675 valid acc 16/16
Epoch 12 loss 0.2120753198716372 valid acc 16/16
Epoch 12 loss 0.7684128808009744 valid acc 16/16
Epoch 12 loss 0.1579761618391216 valid acc 16/16
Epoch 12 loss 0.34112700184064454 valid acc 16/16
Epoch 12 loss 0.46530848789619716 valid acc 14/16
Epoch 12 loss 0.15698677222022972 valid acc 16/16
Epoch 12 loss 0.8771591247484903 valid acc 14/16
Epoch 12 loss 0.43696526335067304 valid acc 14/16
Epoch 12 loss 0.9395148661229893 valid acc 13/16
Epoch 12 loss 0.8113665927371342 valid acc 14/16
Epoch 12 loss 0.5025862806024084 valid acc 15/16
Epoch 12 loss 0.2809678104154415 valid acc 15/16
Epoch 12 loss 0.4940087815072365 valid acc 15/16
Epoch 13 loss 0.032102619826605616 valid acc 15/16
Epoch 13 loss 0.5987536960200801 valid acc 15/16
Epoch 13 loss 0.3660410034361725 valid acc 15/16
Epoch 13 loss 0.30631104676616305 valid acc 15/16
Epoch 13 loss 0.40322631200329967 valid acc 15/16
Epoch 13 loss 0.21580993129233544 valid acc 16/16
Epoch 13 loss 1.1910823514294524 valid acc 15/16
Epoch 13 loss 0.9089754929677832 valid acc 14/16
Epoch 13 loss 0.9053160283810717 valid acc 14/16
Epoch 13 loss 0.40134113185527026 valid acc 14/16
Epoch 13 loss 0.25954938214831424 valid acc 14/16
Epoch 13 loss 0.5381438585907554 valid acc 14/16
Epoch 13 loss 1.0187893410877238 valid acc 14/16
Epoch 13 loss 0.39859707820277945 valid acc 14/16
Epoch 13 loss 0.3343654780997736 valid acc 15/16
Epoch 13 loss 0.20640114460764014 valid acc 15/16
Epoch 13 loss 0.8225419235754368 valid acc 15/16
Epoch 13 loss 0.5501627812819118 valid acc 15/16
Epoch 13 loss 0.5649077989166335 valid acc 15/16
Epoch 13 loss 0.22076159248307742 valid acc 15/16
Epoch 13 loss 0.8467367381088073 valid acc 14/16
Epoch 13 loss 0.0836207238057477 valid acc 14/16
Epoch 13 loss 0.15849766867409443 valid acc 14/16
Epoch 13 loss 0.18932443956133616 valid acc 14/16
Epoch 13 loss 0.24999515765380614 valid acc 15/16
Epoch 13 loss 0.3487871085896115 valid acc 15/16
Epoch 13 loss 0.26074096222689597 valid acc 14/16
Epoch 13 loss 0.5278731707996351 valid acc 15/16
Epoch 13 loss 0.4516103826485766 valid acc 14/16
Epoch 13 loss 0.448857253533789 valid acc 14/16
Epoch 13 loss 0.7046953446247419 valid acc 15/16
Epoch 13 loss 0.11860839383087951 valid acc 15/16
Epoch 13 loss 0.3441970561303716 valid acc 15/16
Epoch 13 loss 0.6390582265685312 valid acc 14/16
Epoch 13 loss 0.9662675237930358 valid acc 16/16
Epoch 13 loss 0.6386793943181622 valid acc 16/16
Epoch 13 loss 0.14835346633005134 valid acc 16/16
Epoch 13 loss 0.1956792280097983 valid acc 16/16
Epoch 13 loss 0.34359211777082754 valid acc 15/16
Epoch 13 loss 0.5920758127953145 valid acc 15/16
Epoch 13 loss 0.14238237138517257 valid acc 15/16
Epoch 13 loss 0.8657832059251618 valid acc 15/16
Epoch 13 loss 0.25083329739202054 valid acc 15/16
Epoch 13 loss 0.20043444514950343 valid acc 16/16
Epoch 13 loss 0.9251403504412128 valid acc 15/16
Epoch 13 loss 0.3275894871121658 valid acc 16/16
Epoch 13 loss 0.5708274311122189 valid acc 16/16
Epoch 13 loss 0.8227730619699032 valid acc 15/16
Epoch 13 loss 0.3035685533644849 valid acc 15/16
Epoch 13 loss 0.2713490351394126 valid acc 15/16
Epoch 13 loss 0.33236713534938256 valid acc 15/16
Epoch 13 loss 0.2884546551526559 valid acc 15/16
Epoch 13 loss 0.416541728325263 valid acc 15/16
Epoch 13 loss 0.3559839305159533 valid acc 16/16
Epoch 13 loss 0.6451935889783262 valid acc 16/16
Epoch 13 loss 0.06378616404159831 valid acc 16/16
Epoch 13 loss 0.49855936045470645 valid acc 15/16
Epoch 13 loss 0.1274050390310898 valid acc 16/16
Epoch 13 loss 0.36278945823915876 valid acc 16/16
Epoch 13 loss 0.14469795858120832 valid acc 15/16
Epoch 13 loss 0.2663732800314679 valid acc 15/16
Epoch 13 loss 0.24574613752802932 valid acc 14/16
Epoch 13 loss 0.29505569098307305 valid acc 15/16
Epoch 14 loss 0.03195370620909577 valid acc 16/16
Epoch 14 loss 0.7802175258619661 valid acc 15/16
Epoch 14 loss 0.3624781348800895 valid acc 15/16
Epoch 14 loss 0.5661176691489971 valid acc 16/16
Epoch 14 loss 0.3082421204315975 valid acc 15/16
Epoch 14 loss 0.2800299484140508 valid acc 16/16
Epoch 14 loss 0.4602894728241146 valid acc 16/16
Epoch 14 loss 0.504541421996129 valid acc 15/16
Epoch 14 loss 0.4960419958951466 valid acc 15/16
Epoch 14 loss 0.15165358856600675 valid acc 15/16
Epoch 14 loss 0.2554690550224973 valid acc 15/16
Epoch 14 loss 0.6460480999017886 valid acc 16/16
Epoch 14 loss 0.9239180869117419 valid acc 16/16
Epoch 14 loss 0.6162060861470032 valid acc 16/16
Epoch 14 loss 0.6048415409170116 valid acc 15/16
Epoch 14 loss 0.5451423509592113 valid acc 15/16
Epoch 14 loss 1.5346564565916514 valid acc 15/16
Epoch 14 loss 0.3538092710725055 valid acc 16/16
Epoch 14 loss 0.2126300647478619 valid acc 15/16
Epoch 14 loss 0.23937856930719212 valid acc 15/16
Epoch 14 loss 0.8725909444773229 valid acc 15/16
Epoch 14 loss 0.32443863516459087 valid acc 15/16
Epoch 14 loss 0.10219801647176108 valid acc 14/16
Epoch 14 loss 0.5952607280678907 valid acc 15/16
Epoch 14 loss 0.36270746150591066 valid acc 14/16
Epoch 14 loss 0.5890678085196193 valid acc 14/16
Epoch 14 loss 0.15221273165417737 valid acc 14/16
Epoch 14 loss 0.5499806382956121 valid acc 14/16
Epoch 14 loss 0.45892403429525924 valid acc 14/16
Epoch 14 loss 0.1877563337949228 valid acc 15/16
Epoch 14 loss 0.31453386599278177 valid acc 15/16
Epoch 14 loss 0.5663876443937446 valid acc 15/16
Epoch 14 loss 0.24913271744140184 valid acc 14/16
Epoch 14 loss 0.4610035404137658 valid acc 15/16
Epoch 14 loss 0.995453699984532 valid acc 15/16
Epoch 14 loss 0.5080046142855341 valid acc 15/16
Epoch 14 loss 0.4943854372588611 valid acc 16/16
Epoch 14 loss 0.3495198386476209 valid acc 15/16
Epoch 14 loss 0.1726735656333998 valid acc 15/16
Epoch 14 loss 0.39264227451406053 valid acc 16/16
Epoch 14 loss 0.18393877332015657 valid acc 14/16
Epoch 14 loss 0.2752341452617464 valid acc 14/16
Epoch 14 loss 0.13886944980905885 valid acc 14/16
Epoch 14 loss 0.1614980446797714 valid acc 15/16
Epoch 14 loss 0.3168475566031599 valid acc 14/16
```