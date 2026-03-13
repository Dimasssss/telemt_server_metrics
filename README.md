# Server Metrics 2026-03-13 00:11:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 65586.5 (18h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1981828
telemt_connections_bad_total 26106
telemt_handshake_timeouts_total 21365
telemt_upstream_connect_attempt_total 13013
telemt_upstream_connect_success_total 12938
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 13013
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6690
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1240
telemt_me_reconnect_attempts_total 18520
telemt_me_reconnect_success_total 9661
telemt_me_reader_eof_total 10444
telemt_me_idle_close_by_peer_total 10443
telemt_me_route_drop_no_conn_total 771256
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1843142
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8630
telemt_desync_full_logged_total 2252
telemt_desync_suppressed_total 6378
telemt_desync_frames_bucket_total{bucket="1_2"} 2272
telemt_desync_frames_bucket_total{bucket="3_10"} 3109
telemt_desync_frames_bucket_total{bucket="gt_10"} 3249
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 10073
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 9648
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 412
telemt_user_connections_total{user="hello"} 1842604
telemt_user_connections_current{user="hello"} 672
telemt_user_octets_from_client{user="hello"} 27409013352 (25.53 GB)
telemt_user_octets_to_client{user="hello"} 651349016064 (606.62 GB)
telemt_user_unique_ips_current{user="hello"} 247
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 95207.0 (26h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 818047
telemt_connections_bad_total 11751
telemt_handshake_timeouts_total 31706
telemt_upstream_connect_attempt_total 24198
telemt_upstream_connect_success_total 24169
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 24198
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12616
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11464
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3434
telemt_me_reconnect_attempts_total 17881
telemt_me_reconnect_success_total 17782
telemt_me_reader_eof_total 18929
telemt_me_idle_close_by_peer_total 18929
telemt_me_route_drop_no_conn_total 264309
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 740280
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3025
telemt_desync_full_logged_total 946
telemt_desync_suppressed_total 2079
telemt_desync_frames_bucket_total{bucket="1_2"} 1206
telemt_desync_frames_bucket_total{bucket="3_10"} 991
telemt_desync_frames_bucket_total{bucket="gt_10"} 828
telemt_pool_swap_total 96
telemt_me_writer_removed_unexpected_total 17956
telemt_me_writer_restored_same_endpoint_total 17773
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 174
telemt_user_connections_total{user="hello"} 742160
telemt_user_connections_current{user="hello"} 195
telemt_user_octets_from_client{user="hello"} 12170068496 (11.33 GB)
telemt_user_octets_to_client{user="hello"} 284480330219 (264.94 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 95206.8 (26h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1703422
telemt_connections_bad_total 8368
telemt_handshake_timeouts_total 113447
telemt_upstream_connect_attempt_total 22141
telemt_upstream_connect_success_total 22131
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 22141
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11767
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10278
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1571
telemt_me_reconnect_attempts_total 18292
telemt_me_reconnect_success_total 17032
telemt_me_reader_eof_total 18029
telemt_me_idle_close_by_peer_total 18028
telemt_me_route_drop_no_conn_total 558665
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1335250
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4975
telemt_desync_full_logged_total 1527
telemt_desync_suppressed_total 3448
telemt_desync_frames_bucket_total{bucket="1_2"} 794
telemt_desync_frames_bucket_total{bucket="3_10"} 1797
telemt_desync_frames_bucket_total{bucket="gt_10"} 2384
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 17194
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 16991
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 162
telemt_user_connections_total{user="hello"} 1334853
telemt_user_connections_current{user="hello"} 376
telemt_user_octets_from_client{user="hello"} 19908106136 (18.54 GB)
telemt_user_octets_to_client{user="hello"} 488208313837 (454.68 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 95207.0 (26h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1059683
telemt_connections_bad_total 13030
telemt_handshake_timeouts_total 71709
telemt_upstream_connect_attempt_total 33383
telemt_upstream_connect_success_total 31122
telemt_upstream_connect_fail_total 2124
telemt_upstream_connect_attempts_per_request{bucket="1"} 33109
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19323
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11713
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2123
telemt_me_keepalive_timeout_total 11256
telemt_me_reconnect_attempts_total 28357
telemt_me_reconnect_success_total 20519
telemt_me_reader_eof_total 22214
telemt_me_idle_close_by_peer_total 22207
telemt_me_route_drop_no_conn_total 374216
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 913018
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1892
telemt_desync_full_logged_total 627
telemt_desync_suppressed_total 1265
telemt_desync_frames_bucket_total{bucket="1_2"} 521
telemt_desync_frames_bucket_total{bucket="3_10"} 743
telemt_desync_frames_bucket_total{bucket="gt_10"} 628
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 20887
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 20497
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 2298
telemt_me_writer_removed_unexpected_minus_restored_total 368
telemt_user_connections_total{user="hello"} 918210
telemt_user_connections_current{user="hello"} 243
telemt_user_octets_from_client{user="hello"} 14359924797 (13.37 GB)
telemt_user_octets_to_client{user="hello"} 364450384238 (339.42 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 95207.1 (26h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1173273
telemt_connections_bad_total 12572
telemt_handshake_timeouts_total 9296
telemt_upstream_connect_attempt_total 28774
telemt_upstream_connect_success_total 28415
telemt_upstream_connect_fail_total 359
telemt_upstream_connect_attempts_per_request{bucket="1"} 28774
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14463
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13791
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 359
telemt_me_keepalive_timeout_total 1824
telemt_me_reconnect_attempts_total 34712
telemt_me_reconnect_success_total 23670
telemt_me_reader_eof_total 24927
telemt_me_idle_close_by_peer_total 24927
telemt_me_seq_mismatch_total 34
telemt_me_route_drop_no_conn_total 438698
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1082341
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 38
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4068
telemt_desync_full_logged_total 1429
telemt_desync_suppressed_total 2639
telemt_desync_frames_bucket_total{bucket="1_2"} 1187
telemt_desync_frames_bucket_total{bucket="3_10"} 1359
telemt_desync_frames_bucket_total{bucket="gt_10"} 1522
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 24290
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 23625
telemt_me_writer_restored_fallback_total 45
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 620
telemt_user_connections_total{user="hello"} 1082198
telemt_user_connections_current{user="hello"} 288
telemt_user_octets_from_client{user="hello"} 13583376472 (12.65 GB)
telemt_user_octets_to_client{user="hello"} 379463351560 (353.40 GB)
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 41
```