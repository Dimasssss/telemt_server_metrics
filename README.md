# Server Metrics 2026-03-11 15:42:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 90929.6 (25h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2243928
telemt_connections_bad_total 39305
telemt_handshake_timeouts_total 53125
telemt_upstream_connect_attempt_total 19011
telemt_upstream_connect_success_total 18999
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 19011
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9562
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9344
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 4893
telemt_me_reconnect_attempts_total 32283
telemt_me_reconnect_success_total 14416
telemt_me_reader_eof_total 15648
telemt_me_idle_close_by_peer_total 15648
telemt_me_route_drop_no_conn_total 830456
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2051356
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10670
telemt_desync_full_logged_total 2897
telemt_desync_suppressed_total 7773
telemt_desync_frames_bucket_total{bucket="1_2"} 2641
telemt_desync_frames_bucket_total{bucket="3_10"} 4117
telemt_desync_frames_bucket_total{bucket="gt_10"} 3912
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 15134
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 14410
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 718
telemt_user_connections_total{user="hello"} 2049803
telemt_user_connections_current{user="hello"} 1364
telemt_user_octets_from_client{user="hello"} 27473470972 (25.59 GB)
telemt_user_octets_to_client{user="hello"} 581476020144 (541.54 GB)
telemt_user_unique_ips_current{user="hello"} 377
telemt_user_unique_ips_recent_window{user="hello"} 205
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 90986.4 (25h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 831150
telemt_connections_bad_total 13686
telemt_handshake_timeouts_total 56283
telemt_upstream_connect_attempt_total 28956
telemt_upstream_connect_success_total 25998
telemt_upstream_connect_fail_total 2958
telemt_upstream_connect_attempts_per_request{bucket="1"} 28956
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12103
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11647
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2958
telemt_me_keepalive_timeout_total 2557
telemt_me_reconnect_attempts_total 20557
telemt_me_reconnect_success_total 18464
telemt_me_reader_eof_total 19527
telemt_me_idle_close_by_peer_total 19524
telemt_me_route_drop_no_conn_total 325813
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 706803
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2897
telemt_desync_full_logged_total 922
telemt_desync_suppressed_total 1975
telemt_desync_frames_bucket_total{bucket="1_2"} 893
telemt_desync_frames_bucket_total{bucket="3_10"} 1042
telemt_desync_frames_bucket_total{bucket="gt_10"} 962
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 18729
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 18441
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 265
telemt_user_connections_total{user="hello"} 709281
telemt_user_connections_current{user="hello"} 512
telemt_user_octets_from_client{user="hello"} 8228137662 (7.66 GB)
telemt_user_octets_to_client{user="hello"} 200556337060 (186.78 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 90986.2 (25h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1441757
telemt_connections_bad_total 8664
telemt_handshake_timeouts_total 124341
telemt_upstream_connect_attempt_total 23893
telemt_upstream_connect_success_total 23600
telemt_upstream_connect_fail_total 293
telemt_upstream_connect_attempts_per_request{bucket="1"} 23893
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12753
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10724
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 123
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 293
telemt_me_keepalive_timeout_total 1587
telemt_me_reconnect_attempts_total 37629
telemt_me_reconnect_success_total 17929
telemt_me_reader_eof_total 19350
telemt_me_idle_close_by_peer_total 19350
telemt_me_route_drop_no_conn_total 525124
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1256292
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3319
telemt_desync_full_logged_total 985
telemt_desync_suppressed_total 2334
telemt_desync_frames_bucket_total{bucket="1_2"} 820
telemt_desync_frames_bucket_total{bucket="3_10"} 1255
telemt_desync_frames_bucket_total{bucket="gt_10"} 1244
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 18789
telemt_me_refill_failed_total 611
telemt_me_writer_restored_same_endpoint_total 17918
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 860
telemt_user_connections_total{user="hello"} 1256011
telemt_user_connections_current{user="hello"} 815
telemt_user_octets_from_client{user="hello"} 15107102425 (14.07 GB)
telemt_user_octets_to_client{user="hello"} 378361621337 (352.38 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 238
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 90986.7 (25h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1035174
telemt_connections_bad_total 77936
telemt_handshake_timeouts_total 101177
telemt_upstream_connect_attempt_total 24341
telemt_upstream_connect_success_total 24341
telemt_upstream_connect_attempts_per_request{bucket="1"} 24341
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13333
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11003
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1014
telemt_me_reconnect_attempts_total 20866
telemt_me_reconnect_success_total 19791
telemt_me_reader_eof_total 20980
telemt_me_idle_close_by_peer_total 20979
telemt_me_seq_mismatch_total 19
telemt_me_route_drop_no_conn_total 338732
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 827776
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 30
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1740
telemt_desync_full_logged_total 668
telemt_desync_suppressed_total 1072
telemt_desync_frames_bucket_total{bucket="1_2"} 627
telemt_desync_frames_bucket_total{bucket="3_10"} 611
telemt_desync_frames_bucket_total{bucket="gt_10"} 502
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 20032
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 19761
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 827096
telemt_user_connections_current{user="hello"} 600
telemt_user_octets_from_client{user="hello"} 9917353792 (9.24 GB)
telemt_user_octets_to_client{user="hello"} 243639297248 (226.91 GB)
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 90986.5 (25h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1145264
telemt_connections_bad_total 6940
telemt_handshake_timeouts_total 11515
telemt_upstream_connect_attempt_total 24621
telemt_upstream_connect_success_total 24510
telemt_upstream_connect_fail_total 111
telemt_upstream_connect_attempts_per_request{bucket="1"} 24621
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12516
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11791
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 198
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 111
telemt_me_keepalive_timeout_total 1952
telemt_me_reconnect_attempts_total 23910
telemt_me_reconnect_success_total 19821
telemt_me_reader_eof_total 20893
telemt_me_idle_close_by_peer_total 20893
telemt_me_route_drop_no_conn_total 408308
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1041841
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4012
telemt_desync_full_logged_total 1456
telemt_desync_suppressed_total 2556
telemt_desync_frames_bucket_total{bucket="1_2"} 1356
telemt_desync_frames_bucket_total{bucket="3_10"} 1502
telemt_desync_frames_bucket_total{bucket="gt_10"} 1154
telemt_pool_swap_total 60
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20203
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 19821
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 382
telemt_user_connections_total{user="hello"} 1041546
telemt_user_connections_current{user="hello"} 763
telemt_user_octets_from_client{user="hello"} 15368193015 (14.31 GB)
telemt_user_octets_to_client{user="hello"} 363943712366 (338.95 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 100
```