# 验收输入案例

以下均为**合成测试资料**，只用于测试规则，不代表任何真实企业的产品或能力。各案例均未指定国家，以国际英语产生候选词；市场自然度仍需当地验证。

## F1 消费电子：Portable Mini Fan

- 产品：便携迷你风扇；手持/桌面两用、可折叠、USB-C 充电、三档风速、无刷电机、低噪、可拆卸底座、锂电池。
- 交易能力：生产工厂；接受 OEM 品牌印刷、颜色和包装定制、批量供货。**没有** ODM、低 MOQ 或防水声明。
- 干扰项：air conditioner、neck fan、waterproof mini fan、mini fan ODM。

## C1 工业设备：Industrial Air Compressor

- 产品：工业用固定式螺杆空气压缩机；变频、无油型号、两级压缩、风冷、7–13 bar、三相电、连续运行、工厂压缩空气系统。
- 交易能力：制造商；提供选型配置定制、批量/项目供货。**没有** OEM、ODM、低 MOQ、进口商/经销商身份声明。
- 干扰项：portable tire inflator、air compressor ODM、air compressor importer。

## B1 家居用品：Stainless Steel Water Bottle

- 产品：不锈钢保温水瓶；双层真空、食品级 304 内胆、500 mL/750 mL、螺旋盖、广口、可重复使用、适合冷/热饮。
- 交易能力：制造商；OEM、品牌印刷、颜色/包装定制、private label、批发/大货供货。**没有** ODM、低 MOQ 或吸管盖声明。
- 干扰项：plastic water bottle、straw lid bottle、water bottle ODM。

## M1 机械零件：CNC Machining Parts

- 产品：按图加工的 CNC 精密机加工零件；铝和不锈钢；CNC 铣削/车削、五轴加工、阳极氧化、紧公差、工业设备应用、小批量与批量生产。
- 交易能力：自有加工工厂；按图定制、OEM、批量供货。**没有** ODM、private label、具体公差数值或低 MOQ 声明。
- 干扰项：CNC machine tools、CNC parts ODM、0.001 mm tolerance parts。

## L1 照明产品：LED Strip Lights

- 产品：LED 灯带；柔性灯带、单色/RGB、COB 型号、12 V/24 V、可调光、IP65 型号、室内装饰/橱柜/标识应用、卷盘供货。
- 交易能力：生产工厂；OEM、长度/色温/包装定制、批发/批量供货。**没有** ODM、低 MOQ、霓虹灯带或太阳能声明。
- 干扰项：LED neon flex、solar LED strip、LED strip ODM。

# 用户示例的品类边界测试

以下词表是用户提供的**候选词**，只用于检查分类与证据门槛；未提供某项规格或配置的产品资料时，不把候选词本身当作事实证明。

## O1 Office Partition Systems

候选：Movable Partition Wall；Operable Wall；Glass Partition System；Office Glass Wall；Acoustic Partition；Transparent Acoustic Partition；Acoustic Pod；Office Phone Booth；Room-in-Room System；Modular Workspace；Office Pod；Plug-and-Play Office Pod；Meeting Room Pod；Flexible Office Space；Office Space Reconfiguration；Operable Acoustic Wall；Folding Partition；Meeting Room Movable Partition；Soundproof Office Partition；Office Space Optimization。

预期：隔断系统、独立舱体、空间方案必须分开；`soundproof` 和透明声学性能需要产品证据。

## O2 Acoustic Pods

候选：Office Acoustic Pod；Meeting Acoustic Pod；Acoustic Phone Booth；Acoustic Meeting Booth；Acoustic Work Pod；Single-Person Acoustic Pod；Multi-Person Acoustic Pod；Private Acoustic Pod；Modular Acoustic Pod；Freestanding Acoustic Pod；Glass Acoustic Pod；Sound-Absorbing Acoustic Pod；Ventilated Acoustic Pod；Acoustic Pod with Lighting；Acoustic Pod for Open-Plan Offices；Acoustic Pod for Coworking Spaces；Acoustic Pod for Private Calls；Acoustic Pod for Video Meetings；Acoustic Pod for Focused Work；Room-in-Room Acoustic Pod。

预期：20 个候选在类别上多数相近，但单/多人、玻璃、通风、照明等配置仍须对照产品目录；`Acoustic Phone Booth` 可能对应独立电话亭产品线。

## O3 Soundproof Office Pods

候选：Single-Person Soundproof Office Pod；Two-Person Soundproof Office Pod；Meeting Soundproof Office Pod；Soundproof Office Phone Booth；Soundproof Work Pod；Private Office Pod；Modular Soundproof Office Pod；Freestanding Soundproof Office Pod；Glass Soundproof Office Pod；Soundproof Office Pod for Calls；Soundproof Office Pod for Video Meetings；Soundproof Office Pod for Focus Work；Soundproof Office Pod for Private Meetings；Soundproof Office Pod for Open-Plan Offices；Soundproof Office Pod for Coworking Spaces；Acoustic Office Pod with Ventilation；Office Pod with Acoustic Insulation；Office Pod with Sound-Absorbing Panels；Office Pod with Integrated Lighting；Room-in-Room Office Pod。

预期：`soundproof` 不能从一般声学材料或吸音板直接推断；产品是否有一人/两人、玻璃等型号需核对。

## E1 eMTB

候选：Full Suspension eMTB；High Power eMTB；1000W Electric Mountain Bike；Bafang M620 eMTB；Mid Drive eMTB；S-Pedelec 45km/h；Long Range eMTB；Smart eMTB；Electric Enduro Bike；Downhill Electric Bike；eMTB with Throttle；Dual Battery eMTB；Belt Drive eMTB；Electric Touring Bike；Electric Hunting Bike；Full Suspension Commuter E-bike；High Torque eMTB；Long Travel eMTB；Premium eMTB；Off-Road Electric Mountain Bike。

参考资料：用户截图指向 [FREY 电助力车目录](https://www.frey-bike.com/electric-bikes/)。预期：用户指定 `eMTB` 为核心；产品目录有山地、通勤等类别，须逐型号核对 1000W、M620、油门、双电池、皮带等信息，不以 OEM/ODM 替换核心词。

## S1 Foreign-Related Litigation Services

候选：Foreign-Related Civil and Commercial Disputes；China Foreign-Related Litigation Lawyer；Cross-Border Dispute Resolution in China；Foreign-Related Contract Dispute Lawyer in China；International Commercial Dispute Lawyer in China；Foreign-Related Criminal Defense Lawyer in China；Foreign-Related Administrative Law Lawyer in China；Foreign-Related Intellectual Property Lawyer in China；Foreign-Related Corporate and Equity Lawyer in China；Foreign-Related Real Estate Lawyer in China；Foreign-Related Construction Dispute Lawyer in China；Foreign-Related Marriage and Family Lawyer in China；Foreign-Related Traffic Accident Lawyer in China；International Commercial Arbitration Lawyer in China；Cross-Border Financial and Securities Lawyer in China；Cross-Border Tax Lawyer in China；Foreign Court Judgment Recognition and Enforcement in China；Foreign Arbitration Award Enforcement in China；Cross-Border Commercial Litigation in China；Legal Services for Foreign Clients in China。

参考资料：用户提供的 `03-九大单元中文版.xlsx` 中“服务定义单元”与“服务能力单元”，以及 [律所官网涉外诉讼页](https://www.zhiminglawyer.com/shewai-susong)。预期：诉讼、仲裁、执行、税务及广义法律服务按实际服务范围与搜索意图区分；不能把整个律所的能力都填进“涉外诉讼”一个核心词下。
