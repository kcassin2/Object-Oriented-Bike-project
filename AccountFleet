package application;

import java.util.ArrayList;

public class AccountFleet{
	
	static SystemAdmin systemAdmin = new SystemAdmin("admin","nimda");
    static ArrayList<OfficeManager> allOfficeManagers = new ArrayList<>();
    static ArrayList<WareHouseManager> allWareHouseManagers = new ArrayList<>();
    static ArrayList<SalesAssociate> allSalesAssociates = new ArrayList<>();
    
    
    public static void addOM(OfficeManager om) {
		allOfficeManagers.add(om);
	}
    
    public static String getOM() {
    	String s = "";
		for (OfficeManager o: allOfficeManagers) {
			s += o.getFirstName() + "," + o.getLastName() + "," + o.getEmail() + "," + o.getUserName() + "," + o.getPassword() + "\n";
		}
		return s;
	}
    
    public static void addWM(WareHouseManager wm) {
		allWareHouseManagers.add(wm);
	}
    
    public static String getWM() {
    	String s = "";
		for (WareHouseManager w: allWareHouseManagers) {
			s += w.getFirstName() + "," + w.getLastName() + "," + w.getEmail() + "," + w.getUserName() + "," + w.getPassword() + "\n";
		}
		return s;
	}
    
    public static void addSA(SalesAssociate sa) {
		allSalesAssociates.add(sa);
	}
    
    public static String getSA() {
    	String s = "";
		for (SalesAssociate sa: allSalesAssociates) {
			s += sa.getFirstName() + "," + sa.getLastName() + "," + sa.getEmail() + "," + sa.getUserName() + "," + sa.getPassword() + "\n";
		}
		return s;
	}
}
