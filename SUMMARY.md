# Summary

* [关于本书](README.md)
* [介绍](introduction.md)
   * [关于这本指南](about_this_user_guide.md)
* [概述](overview/README.md)
   * [特点](overview/features.md)
   * [为什么用 Groovy?](overview/why_groovy.md)
* [教程](tutorials/README.md)
* [安装Gradle](installing_gradle/README.md)
   * [准备阶段](installing_gradle/prerequisites.md)
   * [下载与安装](installing_gradle/download.md)
   * [JVM选项](installing_gradle/jvm_options.md)
* [排除故障](troubleshooting/README.md)
* [构建脚本基础](build_script_basics/README.md)
   * [Projects 和 tasks](build_script_basics/projects_and_tasks.md)
   * [Hello world](build_script_basics/hello_world.md)
   * [快捷的任务定义](build_script_basics/a_shortcut_task_definition.md)
   * [构建脚本代码](build_script_basics/build_scripts_are_code.md)
   * [任务依赖](build_script_basics/task_dependencies.md)
   * [动态任务](build_script_basics/dynamic_tasks.md)
   * [使用已经存在的任务](build_script_basics/manipulating_existing_tasks.md)
   * [短标记法](build_script_basics/shortcut_notations.md)
   * [自定义任务属性](build_script_basics/extra_task_properties.md)
   * [调用 Ant 任务](build_script_basics/using_ant_tasks.md)
   * [使用方法](build_script_basics/using_methods.md)
   * [默认任务](build_script_basics/default_tasks.md)
   * [通过 DAG 配置](build_script_basics/configure_by_dag.md)
* [Java 构建入门](java_quickstart/README.md)
   * [Java 插件](java_quickstart/the_java_plugin.md)
   * [一个基础的 Java 项目](java_quickstart/a_basic_java_project.md)
       * [建立项目](java_quickstart/building_the_project.md)
       * [外部的依赖](java_quickstart/external_dependencies.md)
       * [定制项目](java_quickstart/customizing_the_project.md)
       * [发布 JAR 文件](java_quickstart/publishing_the_jar_file.md)
       * [创建 Eclipse 项目](java_quickstart/creating_an_eclipse_project.md)
       * [总结](java_quickstart/summary.md)
   * [多项目的 Java 构建](java_quickstart/multi-project_java_build.md)
       * [定义一个多项目构建](java_quickstart/defining_a_multi-project_build.md)
       * [通用配置](java_quickstart/common_configuration.md)
       * [项目之间的依赖](java_quickstart/dependencies_between_projects.md)
       * [创建一个发行版本](java_quickstart/creating_a_distribution.md)
* [依赖管理的基础知识](dependency_management_basics/README.md)
   * [什么是依赖管理](dependency_management_basics/what_is_dependency_management.md)
   * [声明你的依赖](dependency_management_basics/a_basic_java_project.md)
   * [依赖配置](dependency_management_basics/dependency_configurations.md)
   * [外部的依赖](dependency_management_basics/external_dependencies.md)
   * [仓库](dependency_management_basics/repositories.md)
   * [发布 artifacts](dependency_management_basics/publishing_artifacts.md)
* [Groovy 快速入门](groovy_quickstart/README.md)
   * [一个基本的 Groovy 项目](groovy_quickstart/a_basic_groovy_project.md)
   * [总结](groovy_quickstart/summary.md)
* [网页应用快速入门](web_application_quickstart/README.md)
   * [构建一个 WAR 文件](web_application_quickstart/building_a_war_file.md)
   * [运行 Web 应用](web_application_quickstart/running_your_web_application.md)
   * [总结](web_application_quickstart/summary.md)
* [使用 Gradle 命令行](using_the_gradle_command-line/README.md)
   * [多任务调用](using_the_gradle_command-line/executing_multiple_tasks.md)
   * [排除任务](using_the_gradle_command-line/excluding_tasks.md)
   * [失败后继续执行构建](using_the_gradle_command-line/continuing_the_build_when_a_failure_occurs.md)
   * [简化任务名](using_the_gradle_command-line/task_name_abbreviation.md)
   * [选择文件构建](using_the_gradle_command-line/selecting_which_build_to_execute.md)
   * [获取构建信息](using_the_gradle_command-line/listing_tasks.md)
       * [项目列表](using_the_gradle_command-line/listing_projects.md)
       * [任务列表](using_the_gradle_command-line/listing_taskss.md)
       * [获取任务具体信息](using_the_gradle_command-line/show_task_usage_details.md)
       * [获取依赖列表](using_the_gradle_command-line/listing_project_dependencies.md)
       * [查看特定依赖](using_the_gradle_command-line/getting_the_insight_into_a_particular_dependency.md)
       * [获取项目属性列表](using_the_gradle_command-line/listing_project_properties.md)
       * [构建日志](using_the_gradle_command-line/profiling_a_build.md)
* [使用 Gradle 图形界面](using_the_gradle_graphical_user_interface/README.md)
   * [任务树](using_the_gradle_graphical_user_interface/task_tree.md)
   * [收藏夹](using_the_gradle_graphical_user_interface/favorities.md)
   * [命令行](using_the_gradle_graphical_user_interface/command_line.md)
   * [设置](using_the_gradle_graphical_user_interface/setup.md)
* [编写构建脚本](writing_build_scripts/README.md)
   * [Gradle 构建语言](writing_build_scripts/the_gradle_build_language.md)
   * [项目 API](writing_build_scripts/the_project_api.md)
       * [标准项目属性](writing_build_scripts/standard_project_properties.md)
   * [脚本 API](writing_build_scripts/the_script_api.md)
   * [声明变量](writing_build_scripts/declaring_variables.md)
       * [局部变量](writing_build_scripts/local_variables.md)
       * [扩展属性](writing_build_scripts/extra_properties.md)
   * [Groovy 基础](writing_build_scripts/some_groovy_basics.md)
       * [Groovy JDK](writing_build_scripts/groovy_jdk.md)
       * [属性存取器](writing_build_scripts/property_accessors.md)
       * [可有可无的圆括号](writing_build_scripts/optional_parentheses_on_method_calls.md)
       * [List 和 Map 集合](writing_build_scripts/list_and_map_literals.md)
       * [闭合作为方法的最后一个参数](writing_build_scripts/closures_as_the_last_parameter_in_a_method.md)
       * [闭合委托对象](writing_build_scripts/closure_delegate.md)
* [深入了解 Tasks](more_about_tasks/README.md)
   * [定义 tasks](more_about_tasks/defining_tasks.md)
   * [定位 tasks](more_about_tasks/locating_tasks.md)
   * [配置 tasks](more_about_tasks/configuring_tasks.md)
   * [给 task 加入依赖](more_about_tasks/adding_dependencies_to_a_task.md)
   * [给 tasks 排序](more_about_tasks/ordering_tasks.md)
   * [给 task 加入描述](more_about_tasks/adding_a_description_to_a_task.md)
   * [替换 tasks](more_about_tasks/replacing_tasks.md)
   * [跳过 tasks](more_about_tasks/skipping_tasks.md)
   * [跳过 up-to-date 的任务](more_about_tasks/skipping_tasks_that_are_up-to-date.md)
   * [Task 规则](more_about_tasks/task_rules.md)
   * [终止 tasks](more_about_tasks/finalizer_tasks.md)
   * [补充](more_about_tasks/extra.md)
       * [Gradle 属性 和 system 属性](more_about_tasks/a.md)
       * [使用其他的脚本配置项目](more_about_tasks/b.md)
       * [配置任意对象](more_about_tasks/c.md)
       * [使用其他的脚本配置任意对象](more_about_tasks/aa.md)
       * [缓存](more_about_tasks/aaa.md)
* [Working With Files](working_with_files/README.md)
   * [Locating files](working_with_files/locating_files.md)
   * [File collections](working_with_files/file_collections.md)
* [Java 插件](the_java_plugin/README.md)
   * [用法](the_java_plugin/java_plugin_usage.md)
   * [资源设置](the_java_plugin/java_plugin_source_sets.md)
   * [任务](the_java_plugin/java_plugin_tasks.md)
   * [项目布局](the_java_plugin/java_plugin_project_layout.md)
   * [依赖管理](the_java_plugin/java_plugin_dependency_management.md)
   * [公共属性](the_java_plugin/java_plugin_convention_properties.md)
   * [使用资源设置](the_java_plugin/java_plugin_working_with_source_sets.md)
   * [Java Plugin Javadoc](the_java_plugin/java_plugin_javadoc.md)
   * [Java Plugin Clean](the_java_plugin/java_plugin_clean)
   * [Java Plugin Resources](the_java_plugin/java_plugin_resources)
   * [Java Plugin CompileJava](the_java_plugin/java_plugin_compilejava.md)
   * [Java Plugin Incremental Java compilation](the_java_plugin/java_plugin_incremental_java_compilation)
   * [Java Plugin Test](the_java_plugin/java_plugin_test)
   * [Java Plugin Uploading](the_java_plugin/java_plugin_uploading.md)
* [War 插件](the_war_plugin/README.md)

