#create a function
function array()
{

        echo "enter the limit"
        read n
        echo "enter the range"
        for((i=0;i<n;i++))
        do
                #a[i]=$i
                if [ $i%11 -eq 0 ]
                then
                         a[i]=$i
                fi
        done

        for i in ${a[@]}
        do
                echo $i
        done

}
#call the function
array

