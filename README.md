## Lab 5 Pseudocode

```markdown
sampX = empty list  
sampY = empty list  
sampZ = empty list  

def collectData(samples):  
    accelX = collection of data in x-direction  
    
    for i in range of samples:  
        sampX.append(accelX)  
    
    accelY = collection of data in y-direction  
    
    for i in range of samples:  
        sampY.append(accelY)  
    
    accelZ = collection of data in z-direction  
    
    for i in range of samples:  
        sampZ.append(accelZ)  
    
    AveX = sum of sampX / length of sampX  
    AveY = sum of sampY / length of sampY  
    AveZ = sum of sampZ / length of sampZ  
    
    return the values of AveX, AveY, and AveZ  

samples = integer value  
call the function collectData(samples)
