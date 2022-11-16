+++
title="... and we got rtl, too!"
description="wanna check out right-to-left layout support? head over here!"
date=2019-08-05
author="mamins1376"

[taxonomies]
tags = ["rtl", "test"]
# categories = ["misc."]
+++

<style type="text/css" rel="stylesheet">
:root:not([dir=rtl]) .only-rtl {
	display: none;
}
:root[dir=rtl] .only-ltr {
	display: none;
}
</style>

Well, you might want to use this theme in a right-to-left language too, We got
you covered! below are two paragraphs with the same content, in two languages
(the other being Persian).

This is the <span class="only-ltr">left-to-right</span>
<span class="only-rtl">right-to-left</span> version of the blog. Since it's not
practical to have two layouts applied at the same time, you can
<a class="only-ltr" href="#">check the other layout (right-to-left) out</a>
<a class="only-rtl" href="#">check the other layout (left-to-right) out</a>
to see for yourself.

این قالب <span class="only-ltr">چپ به راست</span>
<span class="only-rtl">راست به چپ</span> این تم هست. چون عملاً ممکن نیست که هر دو
قالب هم‌زمان اعمال شده باشن، می‌تونید
<a class="only-ltr" href="#">قالب دیگر رو (راست به چپ)</a>
<a class="only-rtl" href="#">قالب دیگر رو (چپ به راست)</a>
امتحان کنید تا خودتون ببینید.
