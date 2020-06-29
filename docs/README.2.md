---
sidebar: auto
---

## Attributes

# width            
  
 - `Number`           
 - `1000`                   
 -  `graph` 的宽度                         


# height           
   
 - `Number`           
 - `8000`                   
 -  `graph` 的高度                         

 
# draggable        
   
 - `Boolean`          
 - `true`                   
 -  是否开启节点拖拽                        
 - 
# linkAddable         

 - `Boolean`          
 - `true`                   
 -  是否开启快捷创建 `link`                 
 - 
# linkEditable        

 - `Boolean`          
 - `true`                   
 -  `link` 是否可编辑                      


# hasMarkLine         

 - `Boolean`          
 - `true`                   
 -  是否开启拖拽辅助线                      

# lineColor       
    
 - `String`           
 - `#666666`                
 -  连线颜色                               

# onLineColor         

 - `String`           
 - `#FF0000`                
 -  鼠标靠近连线时颜色                      


# markLineColor     
  
 - `String`           
 - `#55abfc`                
 -  辅助线颜色                              


# origin     
         
 - `Array`            
 - `[0, 0]`                 
 -  `graph` 的二维坐标系原点                 


# nodeList    
        
 - `Array`            
 - `[]`                     
 -  初始化节点列表                           


# linkList    
        
 - `Array`            
 - `[]`                     
 -  初始化连线列表                           


# graphMenu    
       
 - `Array`            
 - `[]`                     
 -  `graph` 的右键菜单列表配置                


# nodeMenu          
  
 - `Array`            
 - `[]`                     
 -  `node` 右键菜单列表配置                   


# linkMenu            

 - `Array`            
 - `[]`                     
 -  `link` 右键菜单配置                      


# enterIntercept      

 - `Function`         
 - `() => true`             
 -  创建连线进入节点限制                      


# outputIntercept    
 
 - `Function`         
 - `() => true`             
 -  节点生成连线限制                        
