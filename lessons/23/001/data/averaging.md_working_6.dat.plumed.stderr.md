Stderr for source:  averaging.md_working_6.dat   
Download: [zipped raw stdout](averaging.md_working_6.dat.plumed.stdout.txt.zip) - [zipped raw stderr](averaging.md_working_6.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: ACCUMULATE LABEL=a1_denom ARG=a1_weight
Maybe a missing space or a typo?
[fv-az1427-785:07773] *** Process received signal ***
[fv-az1427-785:07773] Signal: Aborted (6)
[fv-az1427-785:07773] Signal code:  (-6)
[fv-az1427-785:07773] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fe2d7842520]
[fv-az1427-785:07773] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fe2d78969fc]
[fv-az1427-785:07773] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fe2d7842476]
[fv-az1427-785:07773] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fe2d78287f3]
[fv-az1427-785:07773] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fe2d7ca2b9e]
[fv-az1427-785:07773] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fe2d7cae20c]
[fv-az1427-785:07773] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fe2d7cae277]
[fv-az1427-785:07773] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fe2d7cae52b]
[fv-az1427-785:07773] [ 8] plumed(+0x12f48)[0x55c3fdf37f48]
[fv-az1427-785:07773] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fe2d7829d90]
[fv-az1427-785:07773] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fe2d7829e40]
[fv-az1427-785:07773] [11] plumed(+0x131e5)[0x55c3fdf381e5]
[fv-az1427-785:07773] *** End of error message ***
</pre>
{% endraw %}
