# 在字符串中查找唯一元素
# 以下代码段可用于查找字符串中所有的唯一元素。 我们使用集合中唯一元素。



    my_string = "aavvccccddddeee"
  
  # converting the string to a set
  temp_set = set(my_string)
  
  # stitching set into a string using join
  new_string = ''.join(temp_set)
  
  print(new_string)
