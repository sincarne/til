PHP has [date/time functions for information about the sun at a given location](http://php.net/date_sun_info). `array date_sun_info (
int $time , float $latitude , float $longitude )` returns an array returning

<dl>
  <dt>
    <em>sunrise</em>
  </dt>

  <dd>
    The time of the sunrise (zenith angle = 90°35').
  </dd>
  <dt>
    <em>sunset</em>
  </dt>
  <dd>
    The time of the sunset (zenith angle = 90°35').
  </dd>
  <dt>
    <em>transit</em>
  </dt>

  <dd>
    The time when the sun is at its zenith, i.e. has reached its topmost point.    
  </dd>
  <dt>
    <em>civil_twilight_begin</em>
  </dt>
  <dd>
    The start of the civil dawn (zenith angle = 96°). It ends at
    <em>sunrise</em>.    
  </dd>
  <dt>
    <em>civil_twilight_end</em>
  </dt>

  <dd>
    The end of the civil dusk (zenith angle = 96°). It starts at
    <em>sunset</em>.
  </dd>
  <dt>
    <em>nautical_twilight_begin</em>
  </dt>
  <dd>
    The start of the nautical dawn (zenith angle = 102°). It ends at
    <em>civil_twilight_begin</em>.    
  </dd>
  <dt>
    <em>nautical_twilight_end</em>
  </dt>
  <dd>
    The end of the nautical dusk (zenith angle = 102°). It starts at
    <em>civil_twilight_end</em>.
  </dd>
  <dt>
    <em>astronomical_twilight_begin</em>
  </dt>
  <dd>
    The start of the astronomical dawn (zenith angle = 108°). It ends at
    <em>nautical_twilight_begin</em>.
  </dd>
  <dt>
    <em>astronomical_twilight_end</em>
  </dt>
  <dd>
    The end of the astronomical dusk (zenith angle = 108°). It starts at
    <em>nautical_twilight_end</em>.
  </dd>
</dl>

There are also [`date_sunrise()`](http://php.net/manual/en/function.date-sunrise.php) and [`date_sunset()`](http://php.net/manual/en/function.date-sunset.php). They return the sunrise or sunset as a string, float, or timestamp.


