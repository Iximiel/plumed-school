Stderr for source:  work/plumed_ex10.dat   
Download: [zipped raw stdout](plumed_ex10.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_ex10.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: MORE_THAN LABEL=fcub ARG=cub SWITCH=SMAP R_0=0.45 D_0=0.0 A=8 B=8
Maybe a missing space or a typo?
[fv-az1432-100:05777] *** Process received signal ***
[fv-az1432-100:05777] Signal: Aborted (6)
[fv-az1432-100:05777] Signal code:  (-6)
[fv-az1432-100:05777] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f1bd6a42520]
[fv-az1432-100:05777] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f1bd6a969fc]
[fv-az1432-100:05777] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f1bd6a42476]
[fv-az1432-100:05777] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f1bd6a287f3]
[fv-az1432-100:05777] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f1bd6ea2b9e]
[fv-az1432-100:05777] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f1bd6eae20c]
[fv-az1432-100:05777] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f1bd6eae277]
[fv-az1432-100:05777] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f1bd6eae52b]
[fv-az1432-100:05777] [ 8] plumed(+0x12f48)[0x561324557f48]
[fv-az1432-100:05777] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f1bd6a29d90]
[fv-az1432-100:05777] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f1bd6a29e40]
[fv-az1432-100:05777] [11] plumed(+0x131e5)[0x5613245581e5]
[fv-az1432-100:05777] *** End of error message ***
</pre>
{% endraw %}
