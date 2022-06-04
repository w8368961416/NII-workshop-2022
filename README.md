# NII-workshop-2022

'''{R Basics}

spelling error in variable

> witty_repair <- c( 'ku70', 'ku80', 'recb')
> witty_repair
```[1] "ku70" "ku80" "recb"

```witty_values <- c(3,10,15)
```witty_repair <- witty_values
```witty_repair[c(1,3)]
```[1]  3 15
```> witty_names=c("X","Y","p53")
```> names(witty_repair)=witty_names
```> witty_repair
```names<-c('a', 'b', 'c')
```sample(names, size=5,replace=TRUE)
```> set.seed(2022)
> sample(names, size=5,replace=TRUE)
[1] "c" "b" "c" "c" "b"
> set.seed(4041)
> sample(names, size=5,replace=TRUE)
[1] "a" "b" "a" "a" "c"
> set.seed(2022)
> sample(names, size=5,replace=TRUE)
[1] "c" "b" "c" "c" "b"
