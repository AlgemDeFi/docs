# Unstaking nASTR

Để lấy lại ASTR của họ, những người nắm giữ nASTR phải trả lại token của họ cho Algem bằng một trong hai tùy chọn unstaking có sẵn:

### Unstaking thông thường

Tùy chọn unstake thông thường sử dụng chức năng tương tự như staking dApps của Astar Network. Sau khi người dùng đã hủy staking token nASTR của mình, Algem sẽ kích hoạt quá trình unstaking trên Astar dApps Staking. Sau khi kết thúc giai đoạn unstaking, Algem sẽ nhận được token ASTR và phân phối chúng trực tiếp vào ví của người dùng.

### Unstaking ngay lập tức

Trong tùy chọn unstaking ngay lập tức, người dùng có thể quyết định hủy stake nASTR của mình và nhận trực tiếp token ASTR của mình mà không cần đợi mười era, như trong trường hợp unstaking thông thường. Đổi lại, Algem tính một khoản phí nhỏ cho dịch vụ. [Thông tin thêm về lệ phí của chúng tôi](../doanh-thu-giao-thuc.md).

Tùy chọn này cũng phụ thuộc vào khả năng của unstaking pool. Pool chứa một số lượng token ASTR nhất định. Hệ thống sẽ từ chối giao dịch nếu pool trống hoặc không có đủ token để đáp ứng yêu cầu unstaking của người dùng.

Doanh thu giao thức cung cấp cho nhóm và việc unstaking thông thường của người dùng ngay lập tức cũng vậy. Tức là, nếu người dùng ngay lập tức unstaking token nASTR của mình bằng cách sử dụng unstaking pool, anh ta sẽ nhận được token ASTR của mình trực tiếp từ pool. Tuy nhiên, Algem cũng sẽ kích hoạt tùy chọn unstaking thông thường trong staking dApps. Sau mười era, token ASTR từ staking dApp sẽ được thêm vào và lấp đầy pool cho phép người dùng khác unstaking ngay lập tức.

Thao tác ở cả 2 phương án đều giống nhau, chỉ có thay đổi về thời gian và phí. ASTR nhận được sau khi unstake không phải là khoản tiền gửi ban đầu mà là số lượng nASTR unstaked.

Tức là, nếu người dùng đã mua hoặc bán token nASTR kể từ lần gửi đầu tiên của anh ấy và đã giải phóng toàn bộ số dư nASTR của mình, anh ấy sẽ nhận được nhiều hoặc ít hơn token ASTR so với khoản tiền gửi ban đầu của mình.

### Hỏi: Khoảng thời gian unstaking là bao lâu?

Thời gian unstaking thay đổi từ 10 ERA đến 13 ERA (khoảng 10-13 ngày).

### Hỏi: Tại sao vậy? Vì thời gian unstaking dApp của Astar Network là 10 ERA

Staking DApp có giới hạn 4 cuộc gọi không liên kết/người dùng trong 10 ngày. Vì hợp đồng Liquid Staking của chúng tôi về cơ bản là một người dùng, Algem nhóm tất cả các cuộc gọi không liên kết thành các nhóm và gửi chúng đến staking dApp 4 lần/10 ngày. Đó là lý do tại sao Nếu bạn unstake ASTR vào đầu chu kỳ này, khoảng thời gian unstaking của bạn sẽ là 13 ERA.
