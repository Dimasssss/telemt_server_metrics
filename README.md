# Server Metrics 2026-03-14 09:03:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 183881.1 (51h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5223241
telemt_connections_bad_total 47354
telemt_handshake_timeouts_total 117702
telemt_upstream_connect_attempt_total 38644
telemt_upstream_connect_success_total 38393
telemt_upstream_connect_fail_total 251
telemt_upstream_connect_attempts_per_request{bucket="1"} 38644
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20814
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17426
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 153
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 251
telemt_me_keepalive_timeout_total 7434
telemt_me_reconnect_attempts_total 38120
telemt_me_reconnect_success_total 26907
telemt_me_reader_eof_total 28874
telemt_me_idle_close_by_peer_total 28873
telemt_me_route_drop_no_conn_total 1976484
telemt_me_route_drop_channel_closed_total 29
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4788360
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 18316
telemt_desync_full_logged_total 4995
telemt_desync_suppressed_total 13321
telemt_desync_frames_bucket_total{bucket="1_2"} 4535
telemt_desync_frames_bucket_total{bucket="3_10"} 6964
telemt_desync_frames_bucket_total{bucket="gt_10"} 6817
telemt_pool_swap_total 159
telemt_me_writer_removed_unexpected_total 27650
telemt_me_refill_failed_total 345
telemt_me_writer_restored_same_endpoint_total 26894
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 743
telemt_user_connections_total{user="hello"} 4789837
telemt_user_connections_current{user="hello"} 1783
telemt_user_octets_from_client{user="hello"} 73311253964 (68.28 GB)
telemt_user_octets_to_client{user="hello"} 1531715842929 (1.39 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 476
telemt_user_unique_ips_recent_window{user="hello"} 259
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 83553.6 (23h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 925551
telemt_connections_bad_total 54188
telemt_handshake_timeouts_total 18409
telemt_upstream_connect_attempt_total 22294
telemt_upstream_connect_success_total 22007
telemt_upstream_connect_fail_total 286
telemt_upstream_connect_attempts_per_request{bucket="1"} 22293
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11974
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9750
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 39
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 244
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 286
telemt_me_keepalive_timeout_total 2180
telemt_me_reconnect_attempts_total 23047
telemt_me_reconnect_success_total 15831
telemt_me_reader_eof_total 16905
telemt_me_idle_close_by_peer_total 16904
telemt_me_route_drop_no_conn_total 308805
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 750910
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2173
telemt_desync_full_logged_total 681
telemt_desync_suppressed_total 1492
telemt_desync_frames_bucket_total{bucket="1_2"} 494
telemt_desync_frames_bucket_total{bucket="3_10"} 933
telemt_desync_frames_bucket_total{bucket="gt_10"} 746
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 16284
telemt_me_refill_failed_total 219
telemt_me_writer_restored_same_endpoint_total 15823
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 453
telemt_user_connections_total{user="hello"} 752809
telemt_user_connections_current{user="hello"} 721
telemt_user_octets_from_client{user="hello"} 8030301209 (7.48 GB)
telemt_user_octets_to_client{user="hello"} 259731394648 (241.89 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 213501.6 (59h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3726121
telemt_connections_bad_total 44206
telemt_handshake_timeouts_total 245820
telemt_upstream_connect_attempt_total 48245
telemt_upstream_connect_success_total 48224
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 48245
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25472
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22499
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 246
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10825
telemt_me_reconnect_attempts_total 42263
telemt_me_reconnect_success_total 37273
telemt_me_reader_eof_total 39582
telemt_me_idle_close_by_peer_total 39581
telemt_me_route_drop_no_conn_total 1279182
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3111110
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10122
telemt_desync_full_logged_total 3439
telemt_desync_suppressed_total 6683
telemt_desync_frames_bucket_total{bucket="1_2"} 1792
telemt_desync_frames_bucket_total{bucket="3_10"} 3673
telemt_desync_frames_bucket_total{bucket="gt_10"} 4657
telemt_pool_swap_total 201
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 37789
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 37232
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 516
telemt_user_connections_total{user="hello"} 3110258
telemt_user_connections_current{user="hello"} 970
telemt_user_octets_from_client{user="hello"} 52619759840 (49.01 GB)
telemt_user_octets_to_client{user="hello"} 1109600058685 (1.01 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 285
telemt_user_unique_ips_recent_window{user="hello"} 168
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 213504.3 (59h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2467417
telemt_connections_bad_total 23357
telemt_handshake_timeouts_total 303121
telemt_upstream_connect_attempt_total 66346
telemt_upstream_connect_success_total 63848
telemt_upstream_connect_fail_total 2361
telemt_upstream_connect_attempts_per_request{bucket="1"} 66072
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38136
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25546
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2360
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20604
telemt_me_reconnect_attempts_total 57611
telemt_me_reconnect_success_total 46189
telemt_me_reader_eof_total 49518
telemt_me_idle_close_by_peer_total 49511
telemt_me_route_drop_no_conn_total 826263
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1938798
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3971
telemt_desync_full_logged_total 1296
telemt_desync_suppressed_total 2675
telemt_desync_frames_bucket_total{bucket="1_2"} 1100
telemt_desync_frames_bucket_total{bucket="3_10"} 1630
telemt_desync_frames_bucket_total{bucket="gt_10"} 1241
telemt_pool_swap_total 186
telemt_me_writer_removed_unexpected_total 46942
telemt_me_refill_failed_total 348
telemt_me_writer_restored_same_endpoint_total 46165
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 753
telemt_user_connections_total{user="hello"} 1944950
telemt_user_connections_current{user="hello"} 461
telemt_user_octets_from_client{user="hello"} 29082924563 (27.09 GB)
telemt_user_octets_to_client{user="hello"} 705582011154 (657.12 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 82937.7 (23h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 909339
telemt_connections_bad_total 12152
telemt_handshake_timeouts_total 11380
telemt_upstream_connect_attempt_total 20928
telemt_upstream_connect_success_total 20366
telemt_upstream_connect_fail_total 562
telemt_upstream_connect_attempts_per_request{bucket="1"} 20928
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9770
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10570
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 562
telemt_me_keepalive_timeout_total 1639
telemt_me_reconnect_attempts_total 66753
telemt_me_reconnect_success_total 16218
telemt_me_reader_eof_total 18196
telemt_me_idle_close_by_peer_total 18195
telemt_me_route_drop_no_conn_total 347340
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 845720
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2214
telemt_desync_full_logged_total 694
telemt_desync_suppressed_total 1520
telemt_desync_frames_bucket_total{bucket="1_2"} 710
telemt_desync_frames_bucket_total{bucket="3_10"} 847
telemt_desync_frames_bucket_total{bucket="gt_10"} 657
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 17942
telemt_me_refill_failed_total 1574
telemt_me_writer_restored_same_endpoint_total 16213
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1724
telemt_user_connections_total{user="hello"} 845637
telemt_user_connections_current{user="hello"} 805
telemt_user_octets_from_client{user="hello"} 15210611496 (14.17 GB)
telemt_user_octets_to_client{user="hello"} 287177304004 (267.45 GB)
telemt_user_unique_ips_current{user="hello"} 216
telemt_user_unique_ips_recent_window{user="hello"} 116
```