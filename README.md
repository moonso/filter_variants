#filter variants

Small script to filter variants based on their frequency.

Right now only works with bg-zipped and tabix indexed 1000G vcf file.

##Installation

```pip install filter-variants```

or

```
>git clone https://github.com/moonso/filter_variants.git
>cd filter_variants
>python setup.py install
```

##Usage

Example files included:

```filter_variants tests/fixtures/test.vcf --thousand_g tests/fixtures/small_1000G.vcf.gz```