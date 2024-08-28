Stderr for source:  contactMatrix.md_working_5.dat   
Download: [zipped raw stdout](contactMatrix.md_working_5.dat.plumed.stdout.txt.zip) - [zipped raw stderr](contactMatrix.md_working_5.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: ONES LABEL=ones64 SIZE=64
Maybe a missing space or a typo?
[fv-az1427-785:06067] *** Process received signal ***
[fv-az1427-785:06067] Signal: Aborted (6)
[fv-az1427-785:06067] Signal code:  (-6)
[fv-az1427-785:06067] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f33f6042520]
[fv-az1427-785:06067] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f33f60969fc]
[fv-az1427-785:06067] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f33f6042476]
[fv-az1427-785:06067] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f33f60287f3]
[fv-az1427-785:06067] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f33f64a2b9e]
[fv-az1427-785:06067] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f33f64ae20c]
[fv-az1427-785:06067] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f33f64ae277]
[fv-az1427-785:06067] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f33f64ae52b]
[fv-az1427-785:06067] [ 8] plumed(+0x12f48)[0x561cb6b6ff48]
[fv-az1427-785:06067] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f33f6029d90]
[fv-az1427-785:06067] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f33f6029e40]
[fv-az1427-785:06067] [11] plumed(+0x131e5)[0x561cb6b701e5]
[fv-az1427-785:06067] *** End of error message ***
</pre>
{% endraw %}
