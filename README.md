# Assessment_1_Covid19
predict new cases (cases_new) in Malaysia


1) Only LSTM, Dense, and Dropout layers should be implemented in the
    model.
2) Nodes in the LSTM layers should be ≤ 64, however, the depth of the model
can be set according to your needs.
3) Window size should be set to 30 days.
4) MAPE error should be lesser than 1% when tested against testing dataset.
𝑀𝑒𝑎𝑛 𝐴𝑏𝑠𝑜𝑙𝑢𝑡𝑒 𝑃𝑒𝑟𝑐𝑒𝑛𝑡𝑎𝑔𝑒 𝐸𝑟𝑟𝑜𝑟 =
𝑀𝑒𝑎𝑛 𝐴𝑏𝑠𝑜𝑙𝑢𝑡𝑒 𝐸𝑟𝑟𝑜𝑟
𝑠𝑢𝑚(𝑎𝑏𝑠(𝑦_𝑎𝑐𝑡𝑢𝑎𝑙))
∗ 100%
5) Training loss should be displayed using TensorBoard. 
