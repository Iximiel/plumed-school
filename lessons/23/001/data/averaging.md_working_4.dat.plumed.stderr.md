Stderr for source:  averaging.md_working_4.dat   
Download: [zipped raw stdout](averaging.md_working_4.dat.plumed.stdout.txt.zip) - [zipped raw stderr](averaging.md_working_4.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: ACCUMULATE LABEL=a1_denom ARG=a1_weight STRIDE=1 CLEAR=100
Maybe a missing space or a typo?
[fv-az1427-785:07713] *** Process received signal ***
[fv-az1427-785:07713] Signal: Aborted (6)
[fv-az1427-785:07713] Signal code:  (-6)
[fv-az1427-785:07713] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fa1d5442520]
[fv-az1427-785:07713] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fa1d54969fc]
[fv-az1427-785:07713] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fa1d5442476]
[fv-az1427-785:07713] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fa1d54287f3]
[fv-az1427-785:07713] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fa1d58a2b9e]
[fv-az1427-785:07713] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fa1d58ae20c]
[fv-az1427-785:07713] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fa1d58ae277]
[fv-az1427-785:07713] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fa1d58ae52b]
[fv-az1427-785:07713] [ 8] plumed(+0x12f48)[0x55e0f63a2f48]
[fv-az1427-785:07713] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fa1d5429d90]
[fv-az1427-785:07713] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fa1d5429e40]
[fv-az1427-785:07713] [11] plumed(+0x131e5)[0x55e0f63a31e5]
[fv-az1427-785:07713] *** End of error message ***
</pre>
{% endraw %}
