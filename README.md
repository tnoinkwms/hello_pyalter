# How to use pyalter

## move axes
```python
# alter.set_axes(axis_num_list, axis_value_list)
alter.set_axes([16,24,13,34,15], [0,255,128,30,100])
```

## get axes value
```python
# Stores values for all joints at that point in time
value_list = alter.get_axes()
```

## axis_index
| Axis | Control Name                   | 255 Value       | 0 Value          | Neutral Value |
|------|-------------------------------|-----------------|------------------|---------------|
| 1    | Eyebrows                      | Angry           | Surprised        | 64            |
| 2    | Pupils (horizontal)           | Left            | Right            | 140           |
| 3    | Pupils (vertical)             | Up              | Down             | 128           |
| 4    | Eyes                          | Closed          | Open             | -             |
| 5-6  | Left/Right cheek              | Raised (smile)  | Lowered          | -             |
| 7    | Lips                          | Puckered        | Relaxed          | -             |
| 8    | Mouth                         | Open            | Closed           | -             |
| 9    | Head tilt                     | Left            | Right            | 128           |
| 10   | Head up/down                  | Down            | Up               | 160           |
| 11   | Head rotate                   | Left            | Right            | 122           |
| 12   | Neck nod                      | Backward        | Forward          | 128           |
| 13   | Hips tilt                     | Left            | Right            | 128           |
| 14   | Waist bend                    | Backward        | Forward          | 128           |
| 15   | Abdomen rotation              | Left            | Right            | 128           |
| 16   | Left shoulder up/down         | Up              | Down             | 128           |
| 17   | Left shoulder forward/back   | Forward         | Back             | 64            |
| 18   | Left armpit open/close       | Open            | Close            | 64            |
| 19   | Left arm lift                 | Up              | Down             | 64            |
| 20   | Left upper arm rotation      | Left            | Right            | 32            |
| 21   | Left elbow bend               | Bent            | Straight         | 32            |
| 22   | Left forearm twist            | Downside        | Upside           | 128           |
| 23   | Left wrist bend               | Straight        | Bent             | 128           |
| 24   | Left wrist side bend          | Left            | Right            | -             |
| 25   | Left thumb                | Bent      | Spread   | N/A           |
| 26   | Left index finger         | Bent      | Spread   | N/A           |
| 27   | Left middle finger        | Bent      | Spread   | N/A           |
| 28   | Left ring/little fingers  | Bent      | Spread   | N/A           |
| 29   | Right shoulder up/down    | Up        | Down     | 128           |
| 30   | Right shoulder forward/back | Forward  | Back     | 64            |
| 31   | Right armpit open/close   | Open      | Close    | 64            |
| 32   | Right arm lift            | Up        | Down     | 64            |
| 33   | Right upper arm rotation  | Right     | Left     | 32            |
| 34   | Right elbow bend          | Bent      | Straight | 32            |
| 35   | Right forearm twist       | Downside  | Upside   | 128           |
| 36   | Right wrist bend          | Straight  | Bent     | 128           |
| 37   | Right wrist side bend     | Right     | Left     | N/A           |
| 38   | Right thumb               | Bent      | Spread   | N/A           |
| 39   | Right index finger        | Bent      | Spread   | N/A           |
| 40   | Right middle finger       | Bent      | Spread   | N/A           |
| 41   | Right ring/little fingers | Bent      | Spread   | N/A           |
| 42   | Whole body raise/lower    | Raised    | Lowered  | 128           |
