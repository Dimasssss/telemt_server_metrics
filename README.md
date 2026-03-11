# Server Metrics 2026-03-11 20:18:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 107466.8 (29h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2729296
telemt_connections_bad_total 54099
telemt_handshake_timeouts_total 61911
telemt_upstream_connect_attempt_total 22726
telemt_upstream_connect_success_total 22714
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 22726
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11458
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11144
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5402
telemt_me_reconnect_attempts_total 35156
telemt_me_reconnect_success_total 17262
telemt_me_reader_eof_total 18650
telemt_me_idle_close_by_peer_total 18650
telemt_me_route_drop_no_conn_total 1027966
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2485765
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12585
telemt_desync_full_logged_total 3501
telemt_desync_suppressed_total 9084
telemt_desync_frames_bucket_total{bucket="1_2"} 3103
telemt_desync_frames_bucket_total{bucket="3_10"} 4839
telemt_desync_frames_bucket_total{bucket="gt_10"} 4643
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 18019
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 17256
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 757
telemt_user_connections_total{user="hello"} 2484116
telemt_user_connections_current{user="hello"} 913
telemt_user_octets_from_client{user="hello"} 37174687328 (34.62 GB)
telemt_user_octets_to_client{user="hello"} 711202679100 (662.36 GB)
telemt_user_unique_ips_current{user="hello"} 288
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 107523.3 (29h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1005580
telemt_connections_bad_total 16558
telemt_handshake_timeouts_total 90368
telemt_upstream_connect_attempt_total 32958
telemt_upstream_connect_success_total 29986
telemt_upstream_connect_fail_total 2972
telemt_upstream_connect_attempts_per_request{bucket="1"} 32958
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14198
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13492
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2087
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2972
telemt_me_keepalive_timeout_total 2881
telemt_me_reconnect_attempts_total 23744
telemt_me_reconnect_success_total 21621
telemt_me_reader_eof_total 22903
telemt_me_idle_close_by_peer_total 22900
telemt_me_route_drop_no_conn_total 380488
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 839651
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3337
telemt_desync_full_logged_total 1082
telemt_desync_suppressed_total 2255
telemt_desync_frames_bucket_total{bucket="1_2"} 1072
telemt_desync_frames_bucket_total{bucket="3_10"} 1182
telemt_desync_frames_bucket_total{bucket="gt_10"} 1083
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 21939
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 21598
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 318
telemt_user_connections_total{user="hello"} 842093
telemt_user_connections_current{user="hello"} 381
telemt_user_octets_from_client{user="hello"} 10155045054 (9.46 GB)
telemt_user_octets_to_client{user="hello"} 245894949780 (229.01 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 107523.2 (29h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1744626
telemt_connections_bad_total 11070
telemt_handshake_timeouts_total 134991
telemt_upstream_connect_attempt_total 27368
telemt_upstream_connect_success_total 27022
telemt_upstream_connect_fail_total 346
telemt_upstream_connect_attempts_per_request{bucket="1"} 27368
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14644
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12240
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 137
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 346
telemt_me_keepalive_timeout_total 2012
telemt_me_reconnect_attempts_total 56876
telemt_me_reconnect_success_total 20500
telemt_me_reader_eof_total 22497
telemt_me_idle_close_by_peer_total 22497
telemt_me_route_drop_no_conn_total 634898
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1533427
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4166
telemt_desync_full_logged_total 1225
telemt_desync_suppressed_total 2941
telemt_desync_frames_bucket_total{bucket="1_2"} 969
telemt_desync_frames_bucket_total{bucket="3_10"} 1582
telemt_desync_frames_bucket_total{bucket="gt_10"} 1615
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 21919
telemt_me_refill_failed_total 1131
telemt_me_writer_restored_same_endpoint_total 20488
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1419
telemt_user_connections_total{user="hello"} 1533063
telemt_user_connections_current{user="hello"} 582
telemt_user_octets_from_client{user="hello"} 19759944277 (18.40 GB)
telemt_user_octets_to_client{user="hello"} 470085252785 (437.80 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 107523.7 (29h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1246218
telemt_connections_bad_total 78227
telemt_handshake_timeouts_total 111326
telemt_upstream_connect_attempt_total 28951
telemt_upstream_connect_success_total 28951
telemt_upstream_connect_attempts_per_request{bucket="1"} 28951
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15773
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13172
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1489
telemt_me_reconnect_attempts_total 28182
telemt_me_reconnect_success_total 23563
telemt_me_reader_eof_total 25025
telemt_me_idle_close_by_peer_total 25024
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 418568
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1021071
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2184
telemt_desync_full_logged_total 818
telemt_desync_suppressed_total 1366
telemt_desync_frames_bucket_total{bucket="1_2"} 778
telemt_desync_frames_bucket_total{bucket="3_10"} 733
telemt_desync_frames_bucket_total{bucket="gt_10"} 673
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 23954
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 23530
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 391
telemt_user_connections_total{user="hello"} 1020197
telemt_user_connections_current{user="hello"} 465
telemt_user_octets_from_client{user="hello"} 12141250072 (11.31 GB)
telemt_user_octets_to_client{user="hello"} 311732359152 (290.32 GB)
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 12199.7 (3h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 184878
telemt_connections_bad_total 5148
telemt_handshake_timeouts_total 2009
telemt_upstream_connect_attempt_total 3520
telemt_upstream_connect_success_total 3519
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3520
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1820
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1683
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 68
telemt_me_reconnect_attempts_total 2875
telemt_me_reconnect_success_total 2846
telemt_me_reader_eof_total 2939
telemt_me_idle_close_by_peer_total 2939
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 62932
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 162225
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 388
telemt_desync_full_logged_total 133
telemt_desync_suppressed_total 255
telemt_desync_frames_bucket_total{bucket="1_2"} 92
telemt_desync_frames_bucket_total{bucket="3_10"} 139
telemt_desync_frames_bucket_total{bucket="gt_10"} 157
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 2879
telemt_me_writer_restored_same_endpoint_total 2821
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 162191
telemt_user_connections_current{user="hello"} 470
telemt_user_octets_from_client{user="hello"} 9475953944 (8.83 GB)
telemt_user_octets_to_client{user="hello"} 54050751776 (50.34 GB)
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 66
```