# Mergesort-carp
Mergesort implementation in carp lang.

Good if you need a stable sort, since Carp uses unstable sort by default.

## Usage
```clojure
(load "https://github.com/GrayJack/Mergesort-carp@master")

(def arr [0 3 4 5 6 1 4 3 5 8])
(defn-do main []
    (let [sorted (MergeSort.sort &arr)])
    (for [i 0 (length sorted)]
        (print* (nth &sorted i)))
    (println* ""))
```
