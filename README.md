# Server Metrics 2026-03-15 18:40:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 73577.6 (20h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2650503
telemt_connections_bad_total 152234
telemt_handshake_timeouts_total 35979
telemt_upstream_connect_attempt_total 14144
telemt_upstream_connect_success_total 14083
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 14144
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7283
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6718
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 15311
telemt_me_reconnect_success_total 10411
telemt_me_reader_eof_total 11129
telemt_me_idle_close_by_peer_total 11129
telemt_me_route_drop_no_conn_total 919807
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2215217
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8554
telemt_desync_full_logged_total 2347
telemt_desync_suppressed_total 6207
telemt_desync_frames_bucket_total{bucket="1_2"} 2113
telemt_desync_frames_bucket_total{bucket="3_10"} 3270
telemt_desync_frames_bucket_total{bucket="gt_10"} 3171
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 10740
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 10400
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 329
telemt_user_connections_total{user="hello"} 2214645
telemt_user_connections_current{user="hello"} 2352
telemt_user_octets_from_client{user="hello"} 33556545736 (31.25 GB)
telemt_user_octets_to_client{user="hello"} 843784750132 (785.84 GB)
telemt_user_unique_ips_current{user="hello"} 669
telemt_user_unique_ips_recent_window{user="hello"} 280
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 73578.3 (20h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1026718
telemt_connections_bad_total 59652
telemt_handshake_timeouts_total 64868
telemt_upstream_connect_attempt_total 18122
telemt_upstream_connect_success_total 18024
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 18122
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9553
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8290
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 40
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 141
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 15206
telemt_me_reconnect_success_total 13993
telemt_me_reader_eof_total 14811
telemt_me_idle_close_by_peer_total 14811
telemt_me_route_drop_no_conn_total 266930
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 794487
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2264
telemt_desync_full_logged_total 778
telemt_desync_suppressed_total 1486
telemt_desync_frames_bucket_total{bucket="1_2"} 783
telemt_desync_frames_bucket_total{bucket="3_10"} 859
telemt_desync_frames_bucket_total{bucket="gt_10"} 622
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 14216
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 13981
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 223
telemt_user_connections_total{user="hello"} 794716
telemt_user_connections_current{user="hello"} 721
telemt_user_octets_from_client{user="hello"} 11479668391 (10.69 GB)
telemt_user_octets_to_client{user="hello"} 300578777488 (279.94 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 236
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 73578.3 (20h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2231771
telemt_connections_bad_total 51243
telemt_handshake_timeouts_total 216536
telemt_upstream_connect_attempt_total 15750
telemt_upstream_connect_success_total 15670
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 15750
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8084
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7507
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 13239
telemt_me_reconnect_success_total 11969
telemt_me_reader_eof_total 12681
telemt_me_idle_close_by_peer_total 12681
telemt_me_route_drop_no_conn_total 583014
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1409346
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3743
telemt_desync_full_logged_total 1343
telemt_desync_suppressed_total 2400
telemt_desync_frames_bucket_total{bucket="1_2"} 856
telemt_desync_frames_bucket_total{bucket="3_10"} 1458
telemt_desync_frames_bucket_total{bucket="gt_10"} 1429
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 12179
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 11950
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 210
telemt_user_connections_total{user="hello"} 1405220
telemt_user_connections_current{user="hello"} 1347
telemt_user_octets_from_client{user="hello"} 26014253292 (24.23 GB)
telemt_user_octets_to_client{user="hello"} 532352694456 (495.79 GB)
telemt_user_unique_ips_current{user="hello"} 393
telemt_user_unique_ips_recent_window{user="hello"} 185
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 73578.2 (20h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1090436
telemt_connections_bad_total 82105
telemt_handshake_timeouts_total 53617
telemt_upstream_connect_attempt_total 171176
telemt_upstream_connect_success_total 170566
telemt_upstream_connect_fail_total 610
telemt_upstream_connect_attempts_per_request{bucket="1"} 171176
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 156994
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13510
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 610
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 61991
telemt_me_reconnect_success_total 13924
telemt_me_reader_eof_total 15809
telemt_me_idle_close_by_peer_total 15809
telemt_me_seq_mismatch_total 27
telemt_me_route_drop_no_conn_total 260691
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 698631
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 44
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1956
telemt_desync_full_logged_total 548
telemt_desync_suppressed_total 1408
telemt_desync_frames_bucket_total{bucket="1_2"} 494
telemt_desync_frames_bucket_total{bucket="3_10"} 754
telemt_desync_frames_bucket_total{bucket="gt_10"} 708
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 15571
telemt_me_refill_failed_total 1504
telemt_me_writer_restored_same_endpoint_total 13888
telemt_me_writer_restored_fallback_total 36
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1647
telemt_user_connections_total{user="hello"} 851142
telemt_user_connections_current{user="hello"} 880
telemt_user_octets_from_client{user="hello"} 15581322009 (14.51 GB)
telemt_user_octets_to_client{user="hello"} 303934855152 (283.06 GB)
telemt_user_msgs_from_client{user="hello"} 3035962
telemt_user_msgs_to_client{user="hello"} 10927629
telemt_user_unique_ips_current{user="hello"} 242
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 73579.4 (20h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1107647
telemt_connections_bad_total 12740
telemt_handshake_timeouts_total 23690
telemt_upstream_connect_attempt_total 16062
telemt_upstream_connect_success_total 15976
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 16062
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7392
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8563
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 88
telemt_me_reconnect_attempts_total 15992
telemt_me_reconnect_success_total 12297
telemt_me_reader_eof_total 13116
telemt_me_idle_close_by_peer_total 13116
telemt_me_route_drop_no_conn_total 280041
telemt_me_route_drop_channel_closed_total 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 919907
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3261
telemt_desync_full_logged_total 1073
telemt_desync_suppressed_total 2188
telemt_desync_frames_bucket_total{bucket="1_2"} 984
telemt_desync_frames_bucket_total{bucket="3_10"} 1200
telemt_desync_frames_bucket_total{bucket="gt_10"} 1077
telemt_pool_swap_total 62
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 12560
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 12289
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 263
telemt_user_connections_total{user="hello"} 919928
telemt_user_connections_current{user="hello"} 999
telemt_user_octets_from_client{user="hello"} 11340945672 (10.56 GB)
telemt_user_octets_to_client{user="hello"} 321488775736 (299.41 GB)
telemt_user_unique_ips_current{user="hello"} 239
telemt_user_unique_ips_recent_window{user="hello"} 119
```