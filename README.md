# Server Metrics 2026-03-13 20:26:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 138485.0 (38h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4402508
telemt_connections_bad_total 37957
telemt_handshake_timeouts_total 106019
telemt_upstream_connect_attempt_total 28954
telemt_upstream_connect_success_total 28757
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 28954
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15842
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12775
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 140
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_timeout_total 6553
telemt_me_reconnect_attempts_total 29642
telemt_me_reconnect_success_total 19526
telemt_me_reader_eof_total 20954
telemt_me_idle_close_by_peer_total 20953
telemt_me_route_drop_no_conn_total 1657707
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4029711
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15993
telemt_desync_full_logged_total 4265
telemt_desync_suppressed_total 11728
telemt_desync_frames_bucket_total{bucket="1_2"} 3992
telemt_desync_frames_bucket_total{bucket="3_10"} 6094
telemt_desync_frames_bucket_total{bucket="gt_10"} 5907
telemt_pool_swap_total 117
telemt_me_writer_removed_unexpected_total 20122
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 19513
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 596
telemt_user_connections_total{user="hello"} 4031850
telemt_user_connections_current{user="hello"} 1297
telemt_user_octets_from_client{user="hello"} 58841209028 (54.80 GB)
telemt_user_octets_to_client{user="hello"} 1272675783121 (1.16 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 363
telemt_user_unique_ips_recent_window{user="hello"} 163
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 38148.6 (10h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 542456
telemt_connections_bad_total 41371
telemt_handshake_timeouts_total 12118
telemt_upstream_connect_attempt_total 10968
telemt_upstream_connect_success_total 10752
telemt_upstream_connect_fail_total 216
telemt_upstream_connect_attempts_per_request{bucket="1"} 10968
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6298
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4239
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 194
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 216
telemt_me_keepalive_timeout_total 1880
telemt_me_reconnect_attempts_total 10213
telemt_me_reconnect_success_total 6794
telemt_me_reader_eof_total 7190
telemt_me_idle_close_by_peer_total 7189
telemt_me_route_drop_no_conn_total 201114
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 470418
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1581
telemt_desync_full_logged_total 423
telemt_desync_suppressed_total 1158
telemt_desync_frames_bucket_total{bucket="1_2"} 337
telemt_desync_frames_bucket_total{bucket="3_10"} 695
telemt_desync_frames_bucket_total{bucket="gt_10"} 549
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 6999
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 6786
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 205
telemt_user_connections_total{user="hello"} 472348
telemt_user_connections_current{user="hello"} 398
telemt_user_octets_from_client{user="hello"} 5084020661 (4.73 GB)
telemt_user_octets_to_client{user="hello"} 149411434244 (139.15 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 168105.4 (46h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3207316
telemt_connections_bad_total 29697
telemt_handshake_timeouts_total 214192
telemt_upstream_connect_attempt_total 37352
telemt_upstream_connect_success_total 37333
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 37352
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19380
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17756
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 191
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 10207
telemt_me_reconnect_attempts_total 31223
telemt_me_reconnect_success_total 28650
telemt_me_reader_eof_total 30343
telemt_me_idle_close_by_peer_total 30342
telemt_me_route_drop_no_conn_total 1098394
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2657857
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8803
telemt_desync_full_logged_total 2942
telemt_desync_suppressed_total 5861
telemt_desync_frames_bucket_total{bucket="1_2"} 1459
telemt_desync_frames_bucket_total{bucket="3_10"} 3217
telemt_desync_frames_bucket_total{bucket="gt_10"} 4127
telemt_pool_swap_total 156
telemt_me_writer_removed_unexpected_total 28997
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 28609
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 347
telemt_user_connections_total{user="hello"} 2657135
telemt_user_connections_current{user="hello"} 729
telemt_user_octets_from_client{user="hello"} 43762116284 (40.76 GB)
telemt_user_octets_to_client{user="hello"} 934719103849 (870.53 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 168105.7 (46h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2080175
telemt_connections_bad_total 22697
telemt_handshake_timeouts_total 197619
telemt_upstream_connect_attempt_total 52488
telemt_upstream_connect_success_total 50050
telemt_upstream_connect_fail_total 2301
telemt_upstream_connect_attempts_per_request{bucket="1"} 52214
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30105
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19781
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2300
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20205
telemt_me_reconnect_attempts_total 43673
telemt_me_reconnect_success_total 34662
telemt_me_reader_eof_total 37209
telemt_me_idle_close_by_peer_total 37202
telemt_me_route_drop_no_conn_total 734897
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1713479
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3686
telemt_desync_full_logged_total 1179
telemt_desync_suppressed_total 2507
telemt_desync_frames_bucket_total{bucket="1_2"} 973
telemt_desync_frames_bucket_total{bucket="3_10"} 1530
telemt_desync_frames_bucket_total{bucket="gt_10"} 1183
telemt_pool_swap_total 147
telemt_me_writer_removed_unexpected_total 35237
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 34638
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 575
telemt_user_connections_total{user="hello"} 1719351
telemt_user_connections_current{user="hello"} 483
telemt_user_octets_from_client{user="hello"} 26714235175 (24.88 GB)
telemt_user_octets_to_client{user="hello"} 644550708630 (600.28 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 37541.5 (10h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 580459
telemt_connections_bad_total 5763
telemt_handshake_timeouts_total 5517
telemt_upstream_connect_attempt_total 8329
telemt_upstream_connect_success_total 8061
telemt_upstream_connect_fail_total 268
telemt_upstream_connect_attempts_per_request{bucket="1"} 8329
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3846
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4195
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 268
telemt_me_keepalive_timeout_total 968
telemt_me_reconnect_attempts_total 28040
telemt_me_reconnect_success_total 6173
telemt_me_reader_eof_total 6977
telemt_me_idle_close_by_peer_total 6976
telemt_me_route_drop_no_conn_total 220050
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 544659
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1479
telemt_desync_full_logged_total 458
telemt_desync_suppressed_total 1021
telemt_desync_frames_bucket_total{bucket="1_2"} 443
telemt_desync_frames_bucket_total{bucket="3_10"} 592
telemt_desync_frames_bucket_total{bucket="gt_10"} 444
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 6913
telemt_me_refill_failed_total 681
telemt_me_writer_restored_same_endpoint_total 6169
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 740
telemt_user_connections_total{user="hello"} 544602
telemt_user_connections_current{user="hello"} 498
telemt_user_octets_from_client{user="hello"} 6843322908 (6.37 GB)
telemt_user_octets_to_client{user="hello"} 173422517532 (161.51 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 60
```