# Server Metrics 2026-03-14 01:12:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 155649.6 (43h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4625975
telemt_connections_bad_total 39794
telemt_handshake_timeouts_total 108020
telemt_upstream_connect_attempt_total 32878
telemt_upstream_connect_success_total 32660
telemt_upstream_connect_fail_total 218
telemt_upstream_connect_attempts_per_request{bucket="1"} 32878
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17851
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14664
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 218
telemt_me_keepalive_timeout_total 6673
telemt_me_reconnect_attempts_total 32717
telemt_me_reconnect_success_total 22583
telemt_me_reader_eof_total 24212
telemt_me_idle_close_by_peer_total 24211
telemt_me_route_drop_no_conn_total 1751927
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4240254
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16679
telemt_desync_full_logged_total 4496
telemt_desync_suppressed_total 12183
telemt_desync_frames_bucket_total{bucket="1_2"} 4159
telemt_desync_frames_bucket_total{bucket="3_10"} 6372
telemt_desync_frames_bucket_total{bucket="gt_10"} 6148
telemt_pool_swap_total 132
telemt_me_writer_removed_unexpected_total 23223
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 22570
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 640
telemt_user_connections_total{user="hello"} 4242112
telemt_user_connections_current{user="hello"} 573
telemt_user_octets_from_client{user="hello"} 62551767988 (58.26 GB)
telemt_user_octets_to_client{user="hello"} 1341263453541 (1.22 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 208
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 55313.3 (15h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 670174
telemt_connections_bad_total 50216
telemt_handshake_timeouts_total 12925
telemt_upstream_connect_attempt_total 15480
telemt_upstream_connect_success_total 15232
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 15480
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8578
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6420
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 24
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_keepalive_timeout_total 2021
telemt_me_reconnect_attempts_total 13870
telemt_me_reconnect_success_total 10427
telemt_me_reader_eof_total 11063
telemt_me_idle_close_by_peer_total 11062
telemt_me_route_drop_no_conn_total 229188
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 543574
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1650
telemt_desync_full_logged_total 448
telemt_desync_suppressed_total 1202
telemt_desync_frames_bucket_total{bucket="1_2"} 351
telemt_desync_frames_bucket_total{bucket="3_10"} 716
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 10682
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 10419
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 255
telemt_user_connections_total{user="hello"} 545525
telemt_user_connections_current{user="hello"} 231
telemt_user_octets_from_client{user="hello"} 5905528641 (5.50 GB)
telemt_user_octets_to_client{user="hello"} 176842471384 (164.70 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 185270.0 (51h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3349357
telemt_connections_bad_total 34317
telemt_handshake_timeouts_total 222626
telemt_upstream_connect_attempt_total 41549
telemt_upstream_connect_success_total 41528
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 41549
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21778
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19519
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10360
telemt_me_reconnect_attempts_total 36960
telemt_me_reconnect_success_total 32003
telemt_me_reader_eof_total 33973
telemt_me_idle_close_by_peer_total 33972
telemt_me_route_drop_no_conn_total 1149624
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2784706
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9167
telemt_desync_full_logged_total 3078
telemt_desync_suppressed_total 6089
telemt_desync_frames_bucket_total{bucket="1_2"} 1545
telemt_desync_frames_bucket_total{bucket="3_10"} 3318
telemt_desync_frames_bucket_total{bucket="gt_10"} 4304
telemt_pool_swap_total 173
telemt_me_writer_removed_unexpected_total 32458
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 31962
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 455
telemt_user_connections_total{user="hello"} 2783945
telemt_user_connections_current{user="hello"} 297
telemt_user_octets_from_client{user="hello"} 44959766136 (41.87 GB)
telemt_user_octets_to_client{user="hello"} 991682368409 (923.58 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 185272.7 (51h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2228537
telemt_connections_bad_total 22924
telemt_handshake_timeouts_total 240589
telemt_upstream_connect_attempt_total 57791
telemt_upstream_connect_success_total 55332
telemt_upstream_connect_fail_total 2322
telemt_upstream_connect_attempts_per_request{bucket="1"} 57517
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33119
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22047
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2321
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20388
telemt_me_reconnect_attempts_total 48127
telemt_me_reconnect_success_total 39099
telemt_me_reader_eof_total 41922
telemt_me_idle_close_by_peer_total 41915
telemt_me_route_drop_no_conn_total 767020
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1787362
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3801
telemt_desync_full_logged_total 1221
telemt_desync_suppressed_total 2580
telemt_desync_frames_bucket_total{bucket="1_2"} 1007
telemt_desync_frames_bucket_total{bucket="3_10"} 1588
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 162
telemt_me_writer_removed_unexpected_total 39720
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 39075
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 621
telemt_user_connections_total{user="hello"} 1793281
telemt_user_connections_current{user="hello"} 165
telemt_user_octets_from_client{user="hello"} 27412426999 (25.53 GB)
telemt_user_octets_to_client{user="hello"} 664070571542 (618.46 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 54705.9 (15h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 681916
telemt_connections_bad_total 7884
telemt_handshake_timeouts_total 8616
telemt_upstream_connect_attempt_total 13564
telemt_upstream_connect_success_total 13183
telemt_upstream_connect_fail_total 381
telemt_upstream_connect_attempts_per_request{bucket="1"} 13564
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6359
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6799
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 381
telemt_me_keepalive_timeout_total 1472
telemt_me_reconnect_attempts_total 42605
telemt_me_reconnect_success_total 10447
telemt_me_reader_eof_total 11680
telemt_me_idle_close_by_peer_total 11679
telemt_me_route_drop_no_conn_total 258174
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 634447
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1640
telemt_desync_full_logged_total 514
telemt_desync_suppressed_total 1126
telemt_desync_frames_bucket_total{bucket="1_2"} 493
telemt_desync_frames_bucket_total{bucket="3_10"} 642
telemt_desync_frames_bucket_total{bucket="gt_10"} 505
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 11543
telemt_me_refill_failed_total 1001
telemt_me_writer_restored_same_endpoint_total 10442
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1096
telemt_user_connections_total{user="hello"} 634346
telemt_user_connections_current{user="hello"} 231
telemt_user_octets_from_client{user="hello"} 10560949388 (9.84 GB)
telemt_user_octets_to_client{user="hello"} 207580314892 (193.32 GB)
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 32
```