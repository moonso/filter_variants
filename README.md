#filter_variants

Small script to filter variants based on their frequency.

Right now only works with bg-zipped and tabix indexed 1000G vcf file.

##Installation

```pip install filer_varaints```

##Usage

Example files included:

```filter_variants tests/fixtures/test.vcf --thousand_g tests/fixtures/small_1000G.vcf.gz```