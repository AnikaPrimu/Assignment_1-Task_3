curl https://www.staff.hsmittweida.de/~wuenschi/data/media/compbiolbook/expression.tab > expression.tab
cat expression.tab
echo -e 'gene\texpr_value' > expression1.tab
cat expression.tab >> expression1.tab
head -n -1 expression1.tab > expressionF.tab
