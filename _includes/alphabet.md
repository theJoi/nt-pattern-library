
{% assign alphabet = "a,b,c,d,e,f,g,h,i,j,k,l,m,n,o,p,q,r,s,t,u,v,w,x,y,z" %}
{% assign alphabet = alphabet | split: ',' %}

{% for x in alphabet %}
{{x}}
{% endfor %}
{% for x in alphabet %}
{{x | upcase}}
{% endfor %}
{% for x in (0..9) %}
{{x}}
{% endfor %}
