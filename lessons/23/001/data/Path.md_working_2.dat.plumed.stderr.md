Stderr for source:  Path.md_working_2.dat   
Download: [zipped raw stdout](Path.md_working_2.dat.plumed.stdout.txt.zip) - [zipped raw stderr](Path.md_working_2.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: LOWEST LABEL=p_mindist ARG=p_data
Maybe a missing space or a typo?
[fv-az1427-785:08673] *** Process received signal ***
[fv-az1427-785:08673] Signal: Aborted (6)
[fv-az1427-785:08673] Signal code:  (-6)
[fv-az1427-785:08673] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fccd5442520]
[fv-az1427-785:08673] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fccd54969fc]
[fv-az1427-785:08673] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fccd5442476]
[fv-az1427-785:08673] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fccd54287f3]
[fv-az1427-785:08673] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fccd58a2b9e]
[fv-az1427-785:08673] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fccd58ae20c]
[fv-az1427-785:08673] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fccd58ae277]
[fv-az1427-785:08673] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fccd58ae52b]
[fv-az1427-785:08673] [ 8] plumed(+0x12f48)[0x561908449f48]
[fv-az1427-785:08673] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fccd5429d90]
[fv-az1427-785:08673] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fccd5429e40]
[fv-az1427-785:08673] [11] plumed(+0x131e5)[0x56190844a1e5]
[fv-az1427-785:08673] *** End of error message ***
</pre>
{% endraw %}
