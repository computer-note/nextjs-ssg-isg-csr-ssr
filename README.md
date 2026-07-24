## 각 브렌치  
[ISG](https://github.com/computer-note/nextjs-ssg-isg-csr-ssr/tree/isg)  
[ISG](https://github.com/computer-note/nextjs-ssg-isg-csr-ssr/tree/ssg)  
[ISG](https://github.com/computer-note/nextjs-ssg-isg-csr-ssr/tree/ssr)   

## 빌드 결과 비교 

### CSR  
| Route(app)                              	| size    	| First Load JS 	|
|-----------------------------------------	|---------	|---------------	|
| o/                                      	| 736 b   	| 87.7 kb       	|  

### SSR  
| Route(app)                              	| size    	| First Load JS 	|
|-----------------------------------------	|---------	|---------------	|
| f/                                      	| 141 b   	| 87.1 kb       	|   

### SSG  
| Route(app)                              	| size    	| First Load JS 	|
|-----------------------------------------	|---------	|---------------	|
| o/                                      	| 141 b   	| 87.1 kb       	| 

### ISG (ISR)  
| Route(app)                              	| size    	| First Load JS 	|
|-----------------------------------------	|---------	|---------------	|
| o/                                      	| 141 b   	| 87.1 kb       	| 
