/**
 * @param {number[]} nums
 * @param {number} target
 * @return {number[]}
 */
function twoNums(nums, target) {
    for(let i=0;i<nums.length;i++){
        for(let j=i+1;j<nums.length;j++){
            if(nums[i]+nums[j] === target){
                return [i,j];
            }
        }
    }
};

let nums = [2,7,11,15];
let targ = 9;
twoNums(nums,targ);
