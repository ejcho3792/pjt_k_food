
if 문 사용하기

<ul>

<li>요리명 : {{foodname}}</li>
<li>요리명(영문) : {{fooden}}</li>
<li>요리설명(영문) : {{foodinen}}</li>
<li>요리재료 : {{foodsource}}</li>

<script>
    if ({{allergie}}!=[] ) {
        <li>※경고 : 알러지 유발재료 {{allergie}} 가 포함되어 있을 수 있습니다.</li>
      } else {
        <li></li>
      }
</script>

</ul>






