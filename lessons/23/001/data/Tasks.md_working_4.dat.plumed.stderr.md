Stderr for source:  Tasks.md_working_4.dat   
Download: [zipped raw stdout](Tasks.md_working_4.dat.plumed.stdout.txt.zip) - [zipped raw stderr](Tasks.md_working_4.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: ONES LABEL=ones SIZE=100
Maybe a missing space or a typo?
[fv-az1427-785:06395] *** Process received signal ***
[fv-az1427-785:06395] Signal: Aborted (6)
[fv-az1427-785:06395] Signal code:  (-6)
[fv-az1427-785:06395] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f2427442520]
[fv-az1427-785:06395] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f24274969fc]
[fv-az1427-785:06395] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f2427442476]
[fv-az1427-785:06395] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f24274287f3]
[fv-az1427-785:06395] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f24278a2b9e]
[fv-az1427-785:06395] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f24278ae20c]
[fv-az1427-785:06395] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f24278ae277]
[fv-az1427-785:06395] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f24278ae52b]
[fv-az1427-785:06395] [ 8] plumed(+0x12f48)[0x55ab964eaf48]
[fv-az1427-785:06395] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f2427429d90]
[fv-az1427-785:06395] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f2427429e40]
[fv-az1427-785:06395] [11] plumed(+0x131e5)[0x55ab964eb1e5]
[fv-az1427-785:06395] *** End of error message ***
</pre>
{% endraw %}
