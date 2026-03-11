# Server Metrics 2026-03-11 21:34:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 112059.0 (31h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2822681
telemt_connections_bad_total 66253
telemt_handshake_timeouts_total 62635
telemt_upstream_connect_attempt_total 23934
telemt_upstream_connect_success_total 23922
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 23934
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12099
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11708
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5443
telemt_me_reconnect_attempts_total 36143
telemt_me_reconnect_success_total 18240
telemt_me_reader_eof_total 19686
telemt_me_idle_close_by_peer_total 19686
telemt_me_route_drop_no_conn_total 1057592
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2557642
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12742
telemt_desync_full_logged_total 3542
telemt_desync_suppressed_total 9200
telemt_desync_frames_bucket_total{bucket="1_2"} 3148
telemt_desync_frames_bucket_total{bucket="3_10"} 4889
telemt_desync_frames_bucket_total{bucket="gt_10"} 4705
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 19013
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 18234
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 773
telemt_user_connections_total{user="hello"} 2555975
telemt_user_connections_current{user="hello"} 675
telemt_user_octets_from_client{user="hello"} 38849215368 (36.18 GB)
telemt_user_octets_to_client{user="hello"} 738192367872 (687.50 GB)
telemt_user_unique_ips_current{user="hello"} 223
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 112115.7 (31h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1028579
telemt_connections_bad_total 17056
telemt_handshake_timeouts_total 90577
telemt_upstream_connect_attempt_total 34444
telemt_upstream_connect_success_total 31452
telemt_upstream_connect_fail_total 2991
telemt_upstream_connect_attempts_per_request{bucket="1"} 34443
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15033
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14117
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2093
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2991
telemt_me_keepalive_timeout_total 6539
telemt_me_reconnect_attempts_total 24716
telemt_me_reconnect_success_total 22571
telemt_me_reader_eof_total 23860
telemt_me_idle_close_by_peer_total 23857
telemt_me_route_drop_no_conn_total 388618
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 860738
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3385
telemt_desync_full_logged_total 1103
telemt_desync_suppressed_total 2282
telemt_desync_frames_bucket_total{bucket="1_2"} 1108
telemt_desync_frames_bucket_total{bucket="3_10"} 1194
telemt_desync_frames_bucket_total{bucket="gt_10"} 1083
telemt_pool_swap_total 92
telemt_me_writer_removed_unexpected_total 22852
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 22548
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 141
telemt_me_writer_removed_unexpected_minus_restored_total 281
telemt_user_connections_total{user="hello"} 863466
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 10437280677 (9.72 GB)
telemt_user_octets_to_client{user="hello"} 261187628892 (243.25 GB)
telemt_user_msgs_from_client{user="hello"} 8579
telemt_user_msgs_to_client{user="hello"} 12990
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 112115.7 (31h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1798248
telemt_connections_bad_total 11437
telemt_handshake_timeouts_total 137772
telemt_upstream_connect_attempt_total 48056
telemt_upstream_connect_success_total 47696
telemt_upstream_connect_fail_total 360
telemt_upstream_connect_attempts_per_request{bucket="1"} 48056
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34055
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13486
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 149
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 360
telemt_me_keepalive_timeout_total 2060
telemt_me_reconnect_attempts_total 63970
telemt_me_reconnect_success_total 20710
telemt_me_reader_eof_total 22921
telemt_me_idle_close_by_peer_total 22921
telemt_me_route_drop_no_conn_total 646903
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1562085
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4215
telemt_desync_full_logged_total 1244
telemt_desync_suppressed_total 2971
telemt_desync_frames_bucket_total{bucket="1_2"} 986
telemt_desync_frames_bucket_total{bucket="3_10"} 1604
telemt_desync_frames_bucket_total{bucket="gt_10"} 1625
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 22344
telemt_me_refill_failed_total 1346
telemt_me_writer_restored_same_endpoint_total 20698
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1634
telemt_user_connections_total{user="hello"} 1581943
telemt_user_connections_current{user="hello"} 437
telemt_user_octets_from_client{user="hello"} 20089761500 (18.71 GB)
telemt_user_octets_to_client{user="hello"} 482913332208 (449.75 GB)
telemt_user_msgs_from_client{user="hello"} 249422
telemt_user_msgs_to_client{user="hello"} 1588794
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 112116.0 (31h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1286693
telemt_connections_bad_total 78303
telemt_handshake_timeouts_total 111965
telemt_upstream_connect_attempt_total 30031
telemt_upstream_connect_success_total 30031
telemt_upstream_connect_attempts_per_request{bucket="1"} 30031
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16344
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13680
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1556
telemt_me_reconnect_attempts_total 29043
telemt_me_reconnect_success_total 24422
telemt_me_reader_eof_total 25942
telemt_me_idle_close_by_peer_total 25941
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 431379
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1060369
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2212
telemt_desync_full_logged_total 832
telemt_desync_suppressed_total 1380
telemt_desync_frames_bucket_total{bucket="1_2"} 781
telemt_desync_frames_bucket_total{bucket="3_10"} 743
telemt_desync_frames_bucket_total{bucket="gt_10"} 688
telemt_pool_swap_total 92
telemt_me_writer_removed_unexpected_total 24829
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 24389
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 407
telemt_user_connections_total{user="hello"} 1059489
telemt_user_connections_current{user="hello"} 259
telemt_user_octets_from_client{user="hello"} 12366921048 (11.52 GB)
telemt_user_octets_to_client{user="hello"} 319560104840 (297.61 GB)
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 16792.2 (4h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 222430
telemt_connections_bad_total 5184
telemt_handshake_timeouts_total 2510
telemt_upstream_connect_attempt_total 4851
telemt_upstream_connect_success_total 4850
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4851
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2490
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2334
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 3984
telemt_me_reconnect_success_total 3946
telemt_me_reader_eof_total 4089
telemt_me_idle_close_by_peer_total 4089
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 75058
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 197376
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 494
telemt_desync_full_logged_total 173
telemt_desync_suppressed_total 321
telemt_desync_frames_bucket_total{bucket="1_2"} 131
telemt_desync_frames_bucket_total{bucket="3_10"} 174
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 3993
telemt_me_writer_restored_same_endpoint_total 3919
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 197338
telemt_user_connections_current{user="hello"} 345
telemt_user_octets_from_client{user="hello"} 9738480620 (9.07 GB)
telemt_user_octets_to_client{user="hello"} 67904400180 (63.24 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 38
```