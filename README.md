-- Define a function to calculate the factorial of a number
function factorial(n)
    if n == 0 then
        return 1
    else
        return n * factorial(n - 1)
    end
end

-- Main program
local number = 5  -- Define a variable 'number' with value 5
print("Factorial of " .. number .. " is " .. factorial(number))

-- Control structures
local sum = 0
for i = 1, 10 do
    sum = sum + i
end
print("Sum of numbers from 1 to 10 is " .. sum)
