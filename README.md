# Ruby-Square-Root
The program show me an error in line 8 and i don't know what im doing bad
print "a: ";
a = gets.chomp.to_i;
print "b: ";
b = gets.chomp.to_i;
print "c: ";
c = gets.chomp.to_i;

x1 = (-b + Math.sqrt((b*b)-4*a*c))/(2*a);
x2 = (-b - Math.sqrt((b*b)-4*a*c))/(2*a);

if (x1 == nil)
	print "The result of x1 doesnt exist";
else
	print "\nThe result of x1 is: ", x1;
end

if (x2 == nil)
	print "The result of x2 doesnt exist";
else
	print "\nThe result of x2 is: ", x2;
end
