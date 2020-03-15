# arrayexample
simple array example with for loop
#!/bin/bash
ITEMS=("BAT","BALL","BALOON")
COUNT=0
for INDEX in ${IMAGE[@]}; do
    echo "check the items: ${IMAGE[COUNT]}"
    COUNT="`expr $COUNT + 1`"
done
