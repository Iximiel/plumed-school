Stderr for source:  INSTRUCTIONS.md_working_3.dat   
Download: [zipped raw stdout](INSTRUCTIONS.md_working_3.dat.plumed.stdout.txt.zip) - [zipped raw stderr](INSTRUCTIONS.md_working_3.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: CMUMD LABEL=left GROUP=lj NSV=1 FIXED=0.5 DCR=0.25 CRSIZE=0.1 WF=0.0001 ASYMM=-1 NINT=0.1 NZ=291
Maybe a missing space or a typo?
[fv-az1427-785:09144] *** Process received signal ***
[fv-az1427-785:09144] Signal: Aborted (6)
[fv-az1427-785:09144] Signal code:  (-6)
[fv-az1427-785:09144] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fd169c42520]
[fv-az1427-785:09144] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fd169c969fc]
[fv-az1427-785:09144] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fd169c42476]
[fv-az1427-785:09144] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fd169c287f3]
[fv-az1427-785:09144] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fd16a0a2b9e]
[fv-az1427-785:09144] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fd16a0ae20c]
[fv-az1427-785:09144] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fd16a0ae277]
[fv-az1427-785:09144] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fd16a0ae52b]
[fv-az1427-785:09144] [ 8] plumed(+0x12f48)[0x5642d05fdf48]
[fv-az1427-785:09144] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fd169c29d90]
[fv-az1427-785:09144] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fd169c29e40]
[fv-az1427-785:09144] [11] plumed(+0x131e5)[0x5642d05fe1e5]
[fv-az1427-785:09144] *** End of error message ***
</pre>
{% endraw %}
