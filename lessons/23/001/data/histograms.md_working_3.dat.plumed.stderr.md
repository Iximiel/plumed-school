Stderr for source:  histograms.md_working_3.dat   
Download: [zipped raw stdout](histograms.md_working_3.dat.plumed.stdout.txt.zip) - [zipped raw stderr](histograms.md_working_3.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: KDE LABEL=hA_kde ARG=x GRID_MIN=0.0 GRID_MAX=3.0 GRID_BIN=100 HEIGHTS=hA_h METRIC=hA_icov
Maybe a missing space or a typo?
[fv-az1427-785:07992] *** Process received signal ***
[fv-az1427-785:07992] Signal: Aborted (6)
[fv-az1427-785:07992] Signal code:  (-6)
[fv-az1427-785:07992] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7ff9b0442520]
[fv-az1427-785:07992] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7ff9b04969fc]
[fv-az1427-785:07992] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7ff9b0442476]
[fv-az1427-785:07992] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7ff9b04287f3]
[fv-az1427-785:07992] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7ff9b08a2b9e]
[fv-az1427-785:07992] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7ff9b08ae20c]
[fv-az1427-785:07992] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7ff9b08ae277]
[fv-az1427-785:07992] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7ff9b08ae52b]
[fv-az1427-785:07992] [ 8] plumed(+0x12f48)[0x56045b312f48]
[fv-az1427-785:07992] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7ff9b0429d90]
[fv-az1427-785:07992] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7ff9b0429e40]
[fv-az1427-785:07992] [11] plumed(+0x131e5)[0x56045b3131e5]
[fv-az1427-785:07992] *** End of error message ***
</pre>
{% endraw %}
