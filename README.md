PHP
===

Doing arrays on PHP
<?PHP 
  
  $names=new array('Phuthuma'=>array(70,56,60),'Simba'=>array(72,87),'Spha'=>92);
  
  foreach($names as name=> $mark)
  {
    echo name.":";
    if(is_array($mark))
    {
      foreach($mark as $test)
      {
        echo $test." ";
      }
    }
    echo $mark."<br>";
  }
  
?>
