# Server Metrics 2026-03-13 04:42:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 81800.6 (22h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2214606
telemt_connections_bad_total 30961
telemt_handshake_timeouts_total 23324
telemt_upstream_connect_attempt_total 16121
telemt_upstream_connect_success_total 16032
telemt_upstream_connect_fail_total 89
telemt_upstream_connect_attempts_per_request{bucket="1"} 16121
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8258
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7729
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 89
telemt_me_keepalive_timeout_total 1304
telemt_me_reconnect_attempts_total 20836
telemt_me_reconnect_success_total 11971
telemt_me_reader_eof_total 12920
telemt_me_idle_close_by_peer_total 12919
telemt_me_route_drop_no_conn_total 844727
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2036665
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8942
telemt_desync_full_logged_total 2322
telemt_desync_suppressed_total 6620
telemt_desync_frames_bucket_total{bucket="1_2"} 2352
telemt_desync_frames_bucket_total{bucket="3_10"} 3226
telemt_desync_frames_bucket_total{bucket="gt_10"} 3364
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 12416
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 11958
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 445
telemt_user_connections_total{user="hello"} 2036090
telemt_user_connections_current{user="hello"} 1007
telemt_user_octets_from_client{user="hello"} 29595648484 (27.56 GB)
telemt_user_octets_to_client{user="hello"} 703113867072 (654.83 GB)
telemt_user_unique_ips_current{user="hello"} 308
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 111421.2 (30h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 899235
telemt_connections_bad_total 11920
telemt_handshake_timeouts_total 39480
telemt_upstream_connect_attempt_total 28252
telemt_upstream_connect_success_total 28221
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 28252
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14598
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13533
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3528
telemt_me_reconnect_attempts_total 21158
telemt_me_reconnect_success_total 21043
telemt_me_reader_eof_total 22429
telemt_me_idle_close_by_peer_total 22429
telemt_me_route_drop_no_conn_total 286817
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 811146
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3232
telemt_desync_full_logged_total 1015
telemt_desync_suppressed_total 2217
telemt_desync_frames_bucket_total{bucket="1_2"} 1292
telemt_desync_frames_bucket_total{bucket="3_10"} 1053
telemt_desync_frames_bucket_total{bucket="gt_10"} 887
telemt_pool_swap_total 114
telemt_me_writer_removed_unexpected_total 21251
telemt_me_writer_restored_same_endpoint_total 21034
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 208
telemt_user_connections_total{user="hello"} 813046
telemt_user_connections_current{user="hello"} 296
telemt_user_octets_from_client{user="hello"} 12998356628 (12.11 GB)
telemt_user_octets_to_client{user="hello"} 313416559467 (291.89 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 111421.0 (30h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1858292
telemt_connections_bad_total 16568
telemt_handshake_timeouts_total 122421
telemt_upstream_connect_attempt_total 25943
telemt_upstream_connect_success_total 25933
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 25943
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12221
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1641
telemt_me_reconnect_attempts_total 21314
telemt_me_reconnect_success_total 20046
telemt_me_reader_eof_total 21228
telemt_me_idle_close_by_peer_total 21227
telemt_me_route_drop_no_conn_total 600068
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1467030
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5115
telemt_desync_full_logged_total 1561
telemt_desync_suppressed_total 3554
telemt_desync_frames_bucket_total{bucket="1_2"} 818
telemt_desync_frames_bucket_total{bucket="3_10"} 1846
telemt_desync_frames_bucket_total{bucket="gt_10"} 2451
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 20236
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 20005
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 190
telemt_user_connections_total{user="hello"} 1466612
telemt_user_connections_current{user="hello"} 496
telemt_user_octets_from_client{user="hello"} 25315664404 (23.58 GB)
telemt_user_octets_to_client{user="hello"} 521044728417 (485.26 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 111421.6 (30h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1149783
telemt_connections_bad_total 13196
telemt_handshake_timeouts_total 74872
telemt_upstream_connect_attempt_total 38342
telemt_upstream_connect_success_total 36059
telemt_upstream_connect_fail_total 2146
telemt_upstream_connect_attempts_per_request{bucket="1"} 38068
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22233
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13735
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2145
telemt_me_keepalive_timeout_total 11388
telemt_me_reconnect_attempts_total 33590
telemt_me_reconnect_success_total 24658
telemt_me_reader_eof_total 26610
telemt_me_idle_close_by_peer_total 26603
telemt_me_route_drop_no_conn_total 409148
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 989325
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1952
telemt_desync_full_logged_total 644
telemt_desync_suppressed_total 1308
telemt_desync_frames_bucket_total{bucket="1_2"} 539
telemt_desync_frames_bucket_total{bucket="3_10"} 761
telemt_desync_frames_bucket_total{bucket="gt_10"} 652
telemt_pool_swap_total 96
telemt_me_writer_removed_unexpected_total 25103
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 24634
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 445
telemt_user_connections_total{user="hello"} 994502
telemt_user_connections_current{user="hello"} 270
telemt_user_octets_from_client{user="hello"} 15238870365 (14.19 GB)
telemt_user_octets_to_client{user="hello"} 392611654614 (365.65 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 111421.4 (30h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1278500
telemt_connections_bad_total 12906
telemt_handshake_timeouts_total 10261
telemt_upstream_connect_attempt_total 35094
telemt_upstream_connect_success_total 34669
telemt_upstream_connect_fail_total 425
telemt_upstream_connect_attempts_per_request{bucket="1"} 35094
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17693
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16788
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 173
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 425
telemt_me_keepalive_timeout_total 1937
telemt_me_reconnect_attempts_total 42869
telemt_me_reconnect_success_total 29137
telemt_me_reader_eof_total 30637
telemt_me_idle_close_by_peer_total 30637
telemt_me_seq_mismatch_total 38
telemt_me_route_drop_no_conn_total 473930
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1182976
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 42
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4318
telemt_desync_full_logged_total 1553
telemt_desync_suppressed_total 2765
telemt_desync_frames_bucket_total{bucket="1_2"} 1306
telemt_desync_frames_bucket_total{bucket="3_10"} 1410
telemt_desync_frames_bucket_total{bucket="gt_10"} 1602
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 29899
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 29087
telemt_me_writer_restored_fallback_total 50
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 762
telemt_user_connections_total{user="hello"} 1182830
telemt_user_connections_current{user="hello"} 462
telemt_user_octets_from_client{user="hello"} 14410757480 (13.42 GB)
telemt_user_octets_to_client{user="hello"} 403315660044 (375.62 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 66
```