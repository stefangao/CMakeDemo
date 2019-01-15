//create projects for eclipse

cmake -E chdir build/release cmake -G "Eclipse CDT4 - Unix Makefiles" -DCMAKE_BUILD_TYPE=release ../../

cmake -E chdir build/debug cmake -G "Eclipse CDT4 - Unix Makefiles" -DCMAKE_BUILD_TYPE=debug ../../
