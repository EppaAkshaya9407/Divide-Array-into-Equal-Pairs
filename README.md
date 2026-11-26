# Divide-Array-into-Equal-Pairs
class Solution:
    def divideArray(self, nums: list[int]) -> bool:
        count=Counter(nums)
        for i,c in count.items():
            if c%2!=0:
                return False
        return True
