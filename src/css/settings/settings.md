/* ==========================================================================
   #MQ
   ========================================================================== */





{# FUTURE BREAKPOINTS #}
{% set phone_large = '22.5em' %} {# 360px #}
{% set tablet = '37.5em' %} {# 600px #}
{% set tablet_large = '56.25em' %} {# 900px #}
{% set desktop = '68.75em' %} {# 1100px #}
{% set desktop_large = '112.5em' %} {# 1800px #}
{% set desktop_larger = '150em' %} {# 2400px #}
{% set header_break = theme.header.breakpoint + 1 ~ 'px' %}





Pre-configuration for Sass MQ.
$breakpoint argument options 

xs..........30em - 480px
sm..........45em - 720px
lg..........64em - 1024px
xl..........75em - 1200px






Prefixes  
xs:   \@xs,
sm:   \@sm,
md:   \@lg,
lg:   \@xl





xs - 480px
@media (min-width: 30em) {}
sm - 720px
@media (min-width: 45em) {}
lg - 1024px
@media (min-width: 64em) {}
xl - 1200px
@media (min-width: 75em) {} 
*/