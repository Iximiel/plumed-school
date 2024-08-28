Stderr for source:  contactMatrix.md_working_6.dat   
Download: [zipped raw stdout](contactMatrix.md_working_6.dat.plumed.stdout.txt.zip) - [zipped raw stderr](contactMatrix.md_working_6.dat.plumed.stderr.txt.zip) 
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
[fv-az1427-785:06113] *** Process received signal ***
[fv-az1427-785:06113] Signal: Aborted (6)
[fv-az1427-785:06113] Signal code:  (-6)
[fv-az1427-785:06113] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fe39a842520]
[fv-az1427-785:06113] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fe39a8969fc]
[fv-az1427-785:06113] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fe39a842476]
[fv-az1427-785:06113] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fe39a8287f3]
[fv-az1427-785:06113] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fe39aca2b9e]
[fv-az1427-785:06113] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fe39acae20c]
[fv-az1427-785:06113] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fe39acae277]
[fv-az1427-785:06113] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fe39acae52b]
[fv-az1427-785:06113] [ 8] plumed(+0x12f48)[0x55f153872f48]
[fv-az1427-785:06113] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fe39a829d90]
[fv-az1427-785:06113] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fe39a829e40]
[fv-az1427-785:06113] [11] plumed(+0x131e5)[0x55f1538731e5]
[fv-az1427-785:06113] *** End of error message ***
</pre>
{% endraw %}
