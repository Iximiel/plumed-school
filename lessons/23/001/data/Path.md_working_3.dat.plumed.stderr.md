Stderr for source:  Path.md_working_3.dat   
Download: [zipped raw stdout](Path.md_working_3.dat.plumed.stdout.txt.zip) - [zipped raw stderr](Path.md_working_3.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: GPATH LABEL=pp ARG=t1,t2 REFERENCE=epath.pdb
Maybe a missing space or a typo?
[fv-az1427-785:08703] *** Process received signal ***
[fv-az1427-785:08703] Signal: Aborted (6)
[fv-az1427-785:08703] Signal code:  (-6)
[fv-az1427-785:08703] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f36cba42520]
[fv-az1427-785:08703] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f36cba969fc]
[fv-az1427-785:08703] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f36cba42476]
[fv-az1427-785:08703] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f36cba287f3]
[fv-az1427-785:08703] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f36cbea2b9e]
[fv-az1427-785:08703] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f36cbeae20c]
[fv-az1427-785:08703] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f36cbeae277]
[fv-az1427-785:08703] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f36cbeae52b]
[fv-az1427-785:08703] [ 8] plumed(+0x12f48)[0x55b3471bbf48]
[fv-az1427-785:08703] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f36cba29d90]
[fv-az1427-785:08703] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f36cba29e40]
[fv-az1427-785:08703] [11] plumed(+0x131e5)[0x55b3471bc1e5]
[fv-az1427-785:08703] *** End of error message ***
</pre>
{% endraw %}
