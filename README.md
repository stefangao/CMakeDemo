1) create projects for eclipse

cmake -E chdir build/release cmake -G "Eclipse CDT4 - Unix Makefiles" -DCMAKE_BUILD_TYPE=release ../../

cmake -E chdir build/debug cmake -G "Eclipse CDT4 - Unix Makefiles" -DCMAKE_BUILD_TYPE=debug ../../

2) open project in eclipse
menu：File -> Import -> general -> Existing projects 
select project_dir/build.

3) build

4) 调试项目时，你需要在菜单：运行/调试配置 里新增配置信息，指定执行文件的路径。
