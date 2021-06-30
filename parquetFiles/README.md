# parquet test data

This folder contains a variety of parquet formats they are intended to be used as part of testing to the Deephaven Community Core Engine. For more information, check out [Deephaven Community Core](https://github.com/deephaven/deephaven-core).


## Table of contents

The following files can be found in this repository:

 - **alltypes_dictionary_v1_IMPALA_NONE.parquet** - Created by Impala, all parquet types in a dictionary with uncompressed. 
 - **alltypes_plain_v1_IMPALA_NONE.parquet** - Created by Impala, all parquet types uncompressed. 
 - **alltypes_plain_v1_IMPALA_SNAPPY.parquet** - Created by Impala, all parquet types with `snappy` compression.
 - **customer_v1_IMPALA_GZIP.parquet** - Created by Impala, with INT96 timestamps and `gzip` compression.
 - **customer_v1_IMPALA_NONE.parquet** - Created by Impala, with INT96 timestamps and uncompressed.
 - **customer_v1_IMPALA_SNAPPY.parquet** - Created by Impala, with INT96 timestamps and `snappy` compression.
 - **eth_cBROTLI_L9.parquet** - Created by PyArrow, ethereum data `brotli` compression level 9.
 - **eth_cBROTLI_PS5.parquet** - Created by PyArrow, version 1 ethereum data `brotli` compression with a page size of 5. 
 - **eth_cGZIP_PS5.parquet** - Created by PyArrow, version 1 ethereum data `gzip` compression with a page size of 5. 
 - **eth_cLZ4_PS5.parquet** - Created by PyArrow, version 1 ethereum data `lz4` compression with a page size of 5. 
 - **eth_cNONE_PS5.parquet** - Created by PyArrow, version 1 ethereum data uncompressed with a page size of 5. 
 - **eth_cSNAPPY_PS5.parquet** - Created by PyArrow, version 1 ethereum data `snappy` compression with a page size of 5. 
 - **eth_cZSTD_L9.parquet** -  Created by PyArrow, version 1 ethereum data `zstd` compression with a page size of 9. 
 - **eth_cZSTD_PS5.parquet** - Created by PyArrow, version 1 ethereum data `zstd` compression with a page size of 5. 
 - **eth_r2_v1_cBROTLI.parquet** - Created by PyArrow, version 1 ethereum data `brotli` compression with a row group size of 2. 
 - **eth_r2_v1_cGZIP.parquet** - Created by PyArrow, version 1 ethereum data `gzip ` compression with a row group size of 2. 
 - **eth_r2_v1_cGZIP_l5.parquet** - Created by PyArrow, ethereum data `gzip` compression level 5.
 - **eth_r2_v1_cLZ4.parquet** - Created by PyArrow, version 1 ethereum data `lz4` compression with a row group size of 2. 
 - **eth_r2_v1_cNONE.parquet** - Created by PyArrow, version 1 ethereum data uncompressed with a row group size of 2. 
 - **eth_r2_v1_cSNAPPY.parquet** - Created by PyArrow, version 1 ethereum data `snappy` compression with a row group size of 2. 
 - **eth_r2_v1_cZSTD.parquet** - Created by PyArrow, version 1 ethereum data `zstd` compression with a row group size of 2. 
 - **eth_r2_v1_cZSTD_l20.parquet** - Created by PyArrow, ethereum data `zstd` compression level209.
 - **eth_r2_v1_p2.parquet** - Created by PyArrow, version 1 ethereum data uncompressed with a row group size of 2 and data page version 2. 
 - **eth_r2_v2_cBROTLI.parquet** - Created by PyArrow, version 2 ethereum data `brotli` compression with a row group size of 2. 
 - **eth_r2_v2_cGZIP.parquet** - Created by PyArrow, version 2 ethereum data `gzip` compression with a row group size of 2. 
 - **eth_r2_v2_cLZ4.parquet** - Created by PyArrow, version 2 ethereum data `lz4` compression with a row group size of 2. 
 - **eth_r2_v2_cNONE.parquet** - Created by PyArrow, version 2 ethereum data uncompressed with a row group size of 2. 
 - **eth_r2_v2_cSNAPPY.parquet** - Created by PyArrow, version 2 ethereum data `snappy` compression with a row group size of 2. 
 - **eth_r2_v2_cZSTD.parquet** - Created by PyArrow, version 2 ethereum data `zstd ` compression with a row group size of 2. 
 - **eth_v1_cBROTLI.parquet** - Created by PyArrow, version 1 ethereum data `brotli` compression. 
 - **eth_v1_cBROTLI_l10.parquet** - Created by PyArrow, ethereum data `brotli` compression level 10.
 - **eth_v1_cBROTLI_l100.parquet** - Created by PyArrow, version 1 ethereum data `brotli` compression level 100.
 - **eth_v1_cGZIP.parquet** - Created by PyArrow, version 1 ethereum data `gzip` compression. 
 - **eth_v1_cGZIP_l5.parquet** - Created by PyArrow, version 1 ethereum data `gzip` compression level 5.
 - **eth_v1_cGZIP_l9.parquet** - Created by PyArrow, version 1 ethereum data `gzip` compression level 9.
 - **eth_v1_cLZ4.parquet** - Created by PyArrow, version 1 ethereum data `lz4` compression. 
 - **eth_v1_cNONE.parquet** - Created by PyArrow, version 1 ethereum data uncompressed. 
 - **eth_v1_cSNAPPY.parquet** - Created by PyArrow, version 1 ethereum data `snappy` compression. 
 - **eth_v1_cZSTD.parquet** - Created by PyArrow, version 1 ethereum data `zstd` compression. 
 - **eth_v1_p1_cBROTLI.parquet** - Created by PyArrow, version 1 ethereum data `brotli` compression with a data page version 1.
 - **eth_v1_p1_cGZIP.parquet** - Created by PyArrow, version 1 ethereum data `gzip` compression with a data page version 1.
 - **eth_v1_p1_cLZ4.parquet** - Created by PyArrow, version 1 ethereum data `lz4` compression with a data page version 1.
 - **eth_v1_p1_cNSAPPY.parquet** - Created by PyArrow, version 1 ethereum data `snappy` compression with a data page version 1.
 - **eth_v1_p1_cZSTD.parquet** - Created by PyArrow, version 1 ethereum data `zstd` compression with a data page version 1.
 - **eth_v1_p2_cBROTLI.parquet** - Created by PyArrow, version 1 ethereum data `brotli` compression with a data page version 2.
 - **eth_v1_p2_cGZIP.parquet** - Created by PyArrow, version 1 ethereum data `gzip` compression with a data page version 2.
 - **eth_v1_p2_cLZ4.parquet** - Created by PyArrow, version 1 ethereum data `lz4` compression with a data page version 2.
 - **eth_v1_p2_cNONE.parquet** - Created by PyArrow, version 1 ethereum data uncompressed with a data page version 2.
 - **eth_v1_p2_cSNAPPY.parquet** - Created by PyArrow, version 1 ethereum data `snappy` compression with a data page version 2.
 - **eth_v1_p2_cZSTD.parquet** - Created by PyArrow, version 1 ethereum data `zstd` compression with a data page version 2.
 - **eth_v2_cBROTLI.parquet** - Created by PyArrow, version 2 ethereum data `brotli` compression.
 - **eth_v2_cGZIP.parquet** - Created by PyArrow, version 2 ethereum data `gzip` compression.
 - **eth_v2_cLZ4.parquet** - Created by PyArrow, version 2 ethereum data `lz4` compression.
 - **eth_v2_cLZ4_PS5.parquet** - Created by PyArrow, version 2 ethereum data `lz4` compression with a page size of 5.
 - **eth_v2_cNONE.parquet** - Created by PyArrow, version 2 ethereum data uncompressed.
 - **eth_v2_cSNAPPY.parquet** - Created by PyArrow, version 2 ethereum data `snappy` compression.
 - **eth_v2_cZSTD.parquet** - Created by PyArrow, version 2 ethereum data `zstd` compression.
 - **eth_v2_fSpark.parquet** - Created by PyArrow, version 2 ethereum data `snappy` compression using spark format.
 - **eth_v2_p1_cBROTLI.parquet** - Created by PyArrow, version 2 ethereum data `brotli` compression with a data page version 1.
 - **eth_v2_p1_cGZIP.parquet** - Created by PyArrow, version 2 ethereum data `gzip` compression with a data page version 1.
 - **eth_v2_p1_cLZ4.parquet** - Created by PyArrow, version 2 ethereum data `lz4` compression with a data page version 1.
 - **eth_v2_p1_cNONE.parquet** - Created by PyArrow, version 2 ethereum data uncompressed with a data page version 1.
 - **eth_v2_p1_cSNAPPY.parquet** - Created by PyArrow, version 2 ethereum data `snappy` compression with a data page version 1.
 - **eth_v2_p1_cZSTD.parquet** - Created by PyArrow, version 2 ethereum data `zstd` compression with a data page version 1.
 - **eth_v2_p2_cBROTLI.parquet** - Created by PyArrow, version 2 ethereum data `brotli` compression with a data page version 2.
 - **eth_v2_p2_cGZIP.parquet** - Created by PyArrow, version 2 ethereum data `gzip` compression with a data page version 2.
 - **eth_v2_p2_cLZ4.parquet** - Created by PyArrow, version 2 ethereum data `lz4` compression with a data page version 2.
 - **eth_v2_p2_cNONE.parquet** - Created by PyArrow, version 2 ethereum data uncompressed with a data page version 2.
 - **eth_v2_p2_cSNAPPY.parquet** - Created by PyArrow, version 2 ethereum data `snappy` compression with a data page version 2.
 - **eth_v2_p2_cZSTD.parquet** - Created by PyArrow, version 2 ethereum data `zesty` compression with a data page version 2.
 - **flow_v1_NULLS_SNAPPY.parquet** - Created by spark, version 1 flow data with null values and `snappy` compression.
 - **london_v1_Whitespace_SNAPPY.parquet** - Created by PyArrow, version 1 London CO2 data with whitespace and `snappy` compression.
 - **nation_dict_MALFORMED.parquet** - Unknown creation, truncated dictionary values
 - **nested_maps_v1_NULLS_SNAPPY.parquet** - Created by spark, version 1 map data with null values and `snappy` compression.
 - **nested_v1_NULLS_SNAPPY.parquet** - Created by spark, version 1 nested data with null values and `snappy` compression.
 - **nonnullable_nested_v1_IMPALA_NULLS_NONE.parquet** - Created by Impala, nested data with nulls, uncompressed.
 - **nullable_nested_v1_IMPALA_NULLS_NONE.parquet** - Created by Impala, nested data with nulls, uncompressed.
 - **nulls_v1_NULLS_SNAPPY.parquet** -  Created by Impala, nested data with nulls, `snappy` compression.
 - **product_v1_CPP_SNAPPY_Whitespace.parquet** - Created by C++, sales data with whitespace and `snappy` compression.
 - **repeated_nested_RUST_NONE.parquet** - Created by Rust, nested and repeating data, uncompressed.
 - **stock_v1_CPP_SNAPPY.parquet** - Created by C++, simulated stock market data with `snappy` compression.
 - **taxi.parquet** - Created by PyArrow, original data set see [Examples](https://github.com/deephaven/examples/tree/main/taxi) for more information



# Source and License

This data was built from data sets publicly available. It is provided here for demonstrative use without any warranty as to the accuracy, reliability, or completeness of the data.