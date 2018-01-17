# Benchmark results

Avec ce TP on obtient les résultats suivants :
| Test Type 	| Test 1 | Test 2 | Test 3 | Test 4 | Test 5 |  Mean  |  Comp  |
|---------------|--------|--------|--------|--------|--------|--------|--------|
| **INT**   	| 4.063s | 4.042s | 4.034s | 4.059s | 4.045s | 4.048s | *ref*  |  
| **FLOAT** 	| 3.749s | 3.750s | 3.764s | 3.754s | 3.757s | 3.754s |  -7.2% |
| **UNROLLED** 	| 3.716s | 3.673s | 3.666s | 3.675s | 3.674s | 3.681s |  -9.0% |
| **SSE** 		| 3.243s | 3.235s | 3.264s | 3.241s | 3.316s | 3.260s | -19.4% |

Ou l'on peut voir que le fait d'utiliser une architecture SIMD peut accélèrer le calcul de 20%. 
