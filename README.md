# πν μκ°
SW Maestro 12κΈ° HACKATHON μν(5/13 ~ 5/14)

![image](/libs/team.PNG)


- #### ν μ΄λ¦ : (μ£Ό)μ§μ­μ΄λ€
- #### νμ₯ : μ΅μ€μ±
- #### νμ : κΉμ€κΈ°,μμ§μ°,μ΄μ² ν¬,μ΄λ―Όμ±,λ°±λμ§



</br></br>
# λ§ν¬
  * ~~[μ€μ  μ¬μ΄νΈ(μΈμμ νμμ)](https://sharedws-unibb.run.goorm.io/)~~
  * [μλλ‘μ΄λ repository](https://github.com/chulhee23/walker-navigator-adnroid)

# πκ°μ 
  μμΈμλ 2013λλΆν° μμ¬κ·κ°μλΉμ€λ₯Ό μννκ³  μ΄ν 5λκ° μ½ 54λ§κ±΄μ μλΉμ€κ° μ§νλμμ΅λλ€. 
  νμ§λ§ λΆμ€ν μ¬νκ΄λ¦¬ νμ 'μ μνμ ' μ΄λΌλ μ§μ μ΄ λμ€κ³  μμ λΏλ§ μλλΌ μ μ°¨ μμ°κΉμ§ κ°μνκ³ 
  μμ΅λλ€. νΉν λ²νκ°μ 1μΈ κ°κ΅¬κ° λ°μ§ν λ§ν¬κ΅¬μ μμ¬κ·κ° μ€μΉ΄μ°νΈλ 10λͺμ λΆκ³Όνκ³ , μ΅κ·Ό κ³΅λΆμ μλ 
  'μ μ² μ΄μΈμ¬κ±΄' λ²νμ§μΈ μμΈ κ°μκ΅¬ λ±μ΄λμ μλΉμ€μ‘°μ°¨ μ κ³΅λμ§ μλ μ§μ­μΌλ‘ νμΈλμμ΅λλ€.<br>
  μ ν¬λ μ΄λ¬ν λ¬Έμ λ₯Ό ν΄κ²°νκ³ μ κ³΅κ³΅ APIλ₯Ό νμ©νμ¬ λ³΄νμμκ² μμ ν κ²½λ‘μ κΈΈμ μ κ³΅ν΄μ£Όλ μλΉμ€λ₯Ό λ§λ€κ² λμμ΅λλ€.
  
</br></br>
# νλ₯΄μλ
+ μΌκ° λ³΄νμ
+ κ΅ν΅μ½μ(λΈμ½μ, μλ λ±)
+ μ΄νκΈΈμ κ±·λ μ¬λ

# πμν€νμ³
![image](/libs/structure.PNG)

</br></br>

# βοΈ μ¬μ©ν κ³΅κ³΅λ°μ΄ν°
+ μμΈνΉλ³μ λ³΄μλ±(κ°λ‘λ±) λ°μ΄ν°
+ μμΈνΉλ³μ CCTV λ°μ΄ν°
+ κ΅ν΅ μ½μ μ¬κ³  λ€λ° μ§μ  λ°μ΄ν°
    - κ°λ¨κ΅¬, κ°λκ΅¬, μμ΄κ΅¬, μ‘νκ΅¬ λ°μ΄ν° νμ μΌλ‘ μ¬μ©


</br></br>
# πλμ κ΅¬ν

1. μΆλ°μ§, λμ°©μ§ μλ ₯
2. μμ λ κ°μ€μΉ κ²½λ‘μΆμ² μκ³ λ¦¬μ¦μ μν΄ μ¬λ¬κ°μ§ κ²½λ‘ μΆμ²
3. κ²½λ‘ μ ν
4. λ€λΉκ²μ΄μ λμ

</br></br>

## κ²½λ‘μΆμ² μκ³ λ¦¬μ¦
* ![equation](https://chart.apis.google.com/chart?cht=tx&chl=(%5Ctext%7Bdanger%20rate%7D)%20%3D%20%5Cfrac%7B%5Ctext%7B%5C%23accident%7D%20%5Ctimes%20(%5Ctext%7B%5C%23death%7D%20%2B%201)%7D%7Bmin_%7B%5Cforall%20point%7D(distance)%7D)

```
findRoute(start, end):
  safe_routes = []
  sectors = seperate_sector(start, end)
  
  for sector in sectors:
    for (cctv, lamp) in random(all cctv, lamp):
      sub_route = Tmap.getRoute(start, (cctv, lamp), end)
      danger_rate = ( accident * (death + 1) ) / min (distance)
      
    route = accumulate(sub_route)
    
    if danger_rate < threshold:
        safe_routes.append(route)
        
  return safe_routes
```

# πμ€ν νλ©΄
## μΉ νλ©΄
![image](/libs/operation_web.PNG)
</br></br>

## λͺ¨λ°μΌ νλ©΄
![image](/libs/operation_mobile.png)
</br></br>
# π νΈμμ±
+ νλ‘μ νΈ μ νμ¬ν­ -> μΉμλΉμ€
+ κΈΈμ°ΎκΈ° μλΉμ€ -> λλΆλΆμ΄ λͺ¨λ°μΌλ‘ μ¬μ©
+ μΉμλΉμ€ -> μ±μΌλ‘ ν¨ν€μ§ -> λͺ¨λ°μΌλ‘ μ¬μ© κ°λ₯ -> μ¬μ©μ± μ¦λ

</br></br>
# π κΈ°λ ν¨κ³Ό
+ μμ  κ·κ°
+ λ³΄νμ λΆμ£Όμ μ¬κ³  κ°μ

