Stderr for source:  INSTRUCTIONS.md_working_3.dat   
Download: [zipped raw stdout](INSTRUCTIONS.md_working_3.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](INSTRUCTIONS.md_working_3.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/RegisterBase.h:211) const Content& PLMD::RegisterBase<Content>::get(const std::vector<void*>&, const string&) const [with Content = PLMD::ActionRegisterPointers; std::string = std::__cxx11::basic_string<char>]
+++ assertion failed: m.count(key)>0
[fv-az1427-785:09152] *** Process received signal ***
[fv-az1427-785:09152] Signal: Aborted (6)
[fv-az1427-785:09152] Signal code:  (-6)
[fv-az1427-785:09152] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fee20442520]
[fv-az1427-785:09152] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fee204969fc]
[fv-az1427-785:09152] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fee20442476]
[fv-az1427-785:09152] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fee204287f3]
[fv-az1427-785:09152] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fee208a2b9e]
[fv-az1427-785:09152] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fee208ae20c]
[fv-az1427-785:09152] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fee208ae277]
[fv-az1427-785:09152] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fee208ae52b]
[fv-az1427-785:09152] [ 8] plumed_master(+0x14274)[0x55cd8fd1e274]
[fv-az1427-785:09152] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fee20429d90]
[fv-az1427-785:09152] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fee20429e40]
[fv-az1427-785:09152] [11] plumed_master(+0x14ed5)[0x55cd8fd1eed5]
[fv-az1427-785:09152] *** End of error message ***
</pre>
{% endraw %}
