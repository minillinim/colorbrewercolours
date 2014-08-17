colorbrewercolours
==================

Easy access to the colorbrewer2.org maps

To see all the available colours just:

  from cb2cols import Cb2Cols as CB2
  cb2 = CB2()
  cb2.demo()


To use a colour / colour set just:

EX: the first three colours from qualset1:

  from cb2cols import Cb2Cols as CB2
  cb2 = CB2()
  col_set = "qualSet1"
  colours = cb2.maps[col_set].values()[0:3]
  
