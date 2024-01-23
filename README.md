# beg.in
class NestedIf
  def showData
    a = 42
    if a > 7
      puts "Yes"
      if a < 50 
        puts "number less than 50"
      end
    end
  end
end

showOutput = NestedIf.new
showOutput.showData
