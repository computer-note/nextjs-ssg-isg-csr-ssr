## 각 브렌치  
[Static Site Generation](https://github.com/computer-note/nextjs-ssg-isg-csr-ssr/tree/ssg)  
[Incremental Static Generation](https://github.com/computer-note/nextjs-ssg-isg-csr-ssr/tree/isg)  
[Client Side Rendering](https://github.com/computer-note/nextjs-ssg-isg-csr-ssr/tree/csr)
[Server Side Rendering](https://github.com/computer-note/nextjs-ssg-isg-csr-ssr/tree/ssr)   

## 빌드 결과 비교 

### SSG  
| Route(app)                              	| size    	| First Load JS 	|
|-----------------------------------------	|---------	|---------------	|
| o/                                      	| 141 b   	| 87.1 kb       	| 

### ISG (ISR)  
| Route(app)                              	| size    	| First Load JS 	|
|-----------------------------------------	|---------	|---------------	|
| o/                                      	| 141 b   	| 87.1 kb       	| 

### CSR  
| Route(app)                              	| size    	| First Load JS 	|
|-----------------------------------------	|---------	|---------------	|
| o/                                      	| 736 b   	| 87.7 kb       	|  

### SSR  
| Route(app)                              	| size    	| First Load JS 	|
|-----------------------------------------	|---------	|---------------	|
| f/                                      	| 141 b   	| 87.1 kb       	|   

