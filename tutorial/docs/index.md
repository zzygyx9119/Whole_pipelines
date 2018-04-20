# Welcome to Whole_pipelines

## Basic
一个较为完整的用以分析Whole Exome Sequencing（WES）的流程，基于luigi。

## Main Entry

* `main.py` - 执行WES分析流程的主入口
* `setting.py` - 主入口的配置文件模板
* `aft_pipelines_analysis/aft_pipelines_main.py` - 在WES分析流程后的，筛选流程、生成网页流程的主入口。


## Project layout

    .
    ├── aft_pipelines_analysis
    │   ├── add_per_info_into_csv.py
    │   ├── aft_pipelines_main.py
    │   ├── csv2bed.py
    │   ├── draw_quality_line.py
    │   ├── extracted_pos_from_vcf.py
    │   ├── filter_pipelines.py
    │   ├── filters.py
    │   ├── filters.pyc
    │   ├── genes_list.py
    │   ├── genes_list.pyc
    │   ├── haplotype
    │   │   ├── __init__.py
    │   │   └── search_possible.py
    │   ├── __init__.py
    │   ├── __init__.pyc
    │   ├── __pycache__
    │   │   └── simpy_summary.cpython-35.pyc
    │   ├── result_csv_plus_depth_info.py
    │   ├── run_add_per_info_into_csv.py
    │   ├── run_info_summary.py
    │   ├── simpy_summary.py
    │   ├── Utils.py
    │   ├── Utils.pyc
    │   └── visualize_mut_heatmap.py
    ├── db_relative_filter
    │   ├── db_association.py
    │   └── __init__.py
    ├── file_tree.txt
    ├── for_trimmomatic_small_script.py
    ├── __init__.py
    ├── __init__.pyc
    ├── luigi.cfg
    ├── luigi_history.db
    ├── luigi_pipelines
    │   ├── GermlinePipelines_gatk4.py
    │   ├── GermlinePipelines.py
    │   ├── GermlinePipelines_to_gemini.py
    │   ├── __init__.py
    │   ├── SomaticPipelines_gatk4.py
    │   ├── SomaticPipelines.py
    │   ├── SomaticPipelines_to_gemini.py
    │   └── test_multi_SomaticPipelines.py
    ├── main.py
    ├── main.pyc
    ├── parse_file_name.py
    ├── parse_file_name.pyc
    ├── parse_PCR2bed.py
    ├── parse_PCR2bed.pyc
    ├── pre_pipelines_analysis
    │   ├── access_seq.py
    │   ├── cal_Cov_script_version.py
    │   ├── __init__.py
    │   └── quality_accessment.py
    ├── README
    │   ├── Command_version.txt
    │   ├── docs
    │   ├── GATKv4_command.txt
    │   └── SelfAdd_content
    ├── setting.py
    ├── setting.pyc
    ├── setting_testing.py
    ├── somatic_filter_script.py
    ├── somatic_filter_script.pyc
    ├── special_fun
    │   ├── Add_cov_ino_in_vcf.py
    │   ├── add_per_info_into_csv_v2.py
    │   ├── collect.py
    │   ├── compare_batch.py
    │   ├── compare_same_sample.py
    │   ├── cov_and_depths_heatmap.py
    │   ├── __init__.py
    │   └── vcf_2_bed.py
    ├── tutorial
    │   ├── docs
    │   │   ├── about.md
    │   │   └── index.md
    │   └── mkdocs.yml
    ├── var_filters_2.py
    └── Workbook.md