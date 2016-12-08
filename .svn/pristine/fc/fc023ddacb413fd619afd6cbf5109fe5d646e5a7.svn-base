package com.cxy.zbs.tools;

import java.io.InputStream;
import java.util.Properties;


public class MySqlConn {
	
	private Properties prop;
	private InputStream in;
	
	public MySqlConn() {
		try {
			prop = new Properties();
			in = MySqlConn.class.getResourceAsStream("jdbc.properties");
			prop.load(in);
		} catch(Exception e) {
			e.printStackTrace();
		}
	}

	
	
	
	
	
}
