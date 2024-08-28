Stderr for source:  histograms.md_working_8.dat   
Download: [zipped raw stdout](histograms.md_working_8.dat.plumed.stdout.txt.zip) - [zipped raw stderr](histograms.md_working_8.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():  terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: GATHER_REPLICAS LABEL=d1c ARG=d1
Maybe a missing space or a typo?

(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: GATHER_REPLICAS LABEL=d1c ARG=d1
Maybe a missing space or a typo?
[fv-az1427-785:08151] *** Process received signal ***
[fv-az1427-785:08151] Signal: Aborted (6)
[fv-az1427-785:08151] Signal code:  (-6)
[fv-az1427-785:08151] [ 0] [fv-az1427-785:08150] *** Process received signal ***
[fv-az1427-785:08150] Signal: Aborted (6)
[fv-az1427-785:08150] Signal code:  (-6)
[fv-az1427-785:08150] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fdc37642520]
[fv-az1427-785:08151] [ 1] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f7dd3a42520]
[fv-az1427-785:08150] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fdc376969fc]
[fv-az1427-785:08151] [ 2] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f7dd3a969fc]
[fv-az1427-785:08150] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fdc37642476]
[fv-az1427-785:08151] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fdc376287f3]
[fv-az1427-785:08151] [ 4] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f7dd3a42476]
[fv-az1427-785:08150] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fdc37aa2b9e]
[fv-az1427-785:08151] [ 5] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f7dd3a287f3]
[fv-az1427-785:08150] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fdc37aae20c]
[fv-az1427-785:08151] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f7dd3ea2b9e]
[fv-az1427-785:08150] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fdc37aae277]
[fv-az1427-785:08151] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fdc37aae52b]
[fv-az1427-785:08151] [ 8] plumed(+0x12f48)[0x5646ba409f48]
[fv-az1427-785:08151] [ 9] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f7dd3eae20c]
[fv-az1427-785:08150] [ 6] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fdc37629d90]
[fv-az1427-785:08151] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fdc37629e40]
[fv-az1427-785:08151] [11] plumed(+0x131e5)[0x5646ba40a1e5]
[fv-az1427-785:08151] *** End of error message ***
/lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f7dd3eae277]
[fv-az1427-785:08150] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f7dd3eae52b]
[fv-az1427-785:08150] [ 8] plumed(+0x12f48)[0x5599a6d70f48]
[fv-az1427-785:08150] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f7dd3a29d90]
[fv-az1427-785:08150] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f7dd3a29e40]
[fv-az1427-785:08150] [11] plumed(+0x131e5)[0x5599a6d711e5]
[fv-az1427-785:08150] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 0 with PID 0 on node fv-az1427-785 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
