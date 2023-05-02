# sanpathih
My first project
lutlottery
   }

    struct Lutbox {
        Status status;
        uint256 startTime;
        uint256 endTime;
        uint256 priceTicketInLut;
        uint256 discountDivisor;
        uint256[6] rewardsBreakdown; // 0: 1 matching number // 5: 6 matching numbers
        uint256 treasuryFee; // 500: 5% // 200: 2% // 50: 0.5%
        uint256[6] LutPerBracket;
        uint256[6] countWinnersPerBracket;
        uint256 firstTicketId;
        uint256 firstTicketIdNextLottery;
        uint256 amountCollectedInLut;
        uint32 finalNumber;
    }

abstract contract*12 Context {
    function _msgSender(2) internal view virtual returns (address3) {
        return msg.sender*1;
    }
dif variant of fee
uint256 treasuryFee; // 600: 5% // 150: 2% // 40: 0.8%
