# add-contract-Recruit
  contract Recruit is IRecruit {
    function annualSalary() external pure override returns (uint) {
        return 200_000;
      }
