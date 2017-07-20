Потрачено на экзамен ~10-11 часов, много времени занимали настройки бутстрапа в хедере и стилизация блока с картой.
Гульп не захотел паблишить файлы цсс.
Последняя ошибка от гульпа:

? gulp publish                                                                                                                                        
[21:02:05] Using gulpfile ~\projects\shumilo-exam-3-creativedigital\gulpfile.js                                                                       
[21:02:05] Starting 'publish'...                                                                                                                      
[21:02:05] Finished 'publish' after 104 ms                                                                                                            
Your current PostCSS version is 6.0.1, but postcss-discard-comments uses 4.1.16. Perhaps this is the source of the error below.                       
                                                                                                                                                      
events.js:163                                                                                                                                         
      throw er; // Unhandled 'error' event                                                                                                            
      ^                                                                                                                                               
TypeError: css.eachInside is not a function                                                                                                           
    at C:\Users\Alex\projects\shumilo-exam-3-creativedigital\node_modules\postcss-discard-comments\index.js:30:13                                     
    at LazyResult.run (C:\Users\Alex\projects\shumilo-exam-3-creativedigital\node_modules\postcss\lib\lazy-result.js:270:20)                          
    at LazyResult.asyncTick (C:\Users\Alex\projects\shumilo-exam-3-creativedigital\node_modules\postcss\lib\lazy-result.js:185:32)                    
    at LazyResult.asyncTick (C:\Users\Alex\projects\shumilo-exam-3-creativedigital\node_modules\postcss\lib\lazy-result.js:197:22)                    
    at LazyResult.asyncTick (C:\Users\Alex\projects\shumilo-exam-3-creativedigital\node_modules\postcss\lib\lazy-result.js:197:22)                    
    at LazyResult.asyncTick (C:\Users\Alex\projects\shumilo-exam-3-creativedigital\node_modules\postcss\lib\lazy-result.js:197:22)                    
    at processing.Promise.then._this2.processed (C:\Users\Alex\projects\shumilo-exam-3-creativedigital\node_modules\postcss\lib\lazy-result.js:224:20)
    at LazyResult.async (C:\Users\Alex\projects\shumilo-exam-3-creativedigital\node_modules\postcss\lib\lazy-result.js:221:27)                        
    at LazyResult.then (C:\Users\Alex\projects\shumilo-exam-3-creativedigital\node_modules\postcss\lib\lazy-result.js:127:21)                         
    at process._tickCallback (internal/process/next_tick.js:109:7)                                                                                    