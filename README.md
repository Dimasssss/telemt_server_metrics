# Server Metrics 2026-03-13 15:25:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 120437.9 (33h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3743002
telemt_connections_bad_total 37422
telemt_handshake_timeouts_total 75927
telemt_upstream_connect_attempt_total 23448
telemt_upstream_connect_success_total 23313
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 23448
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12016
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11237
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 2193
telemt_me_reconnect_attempts_total 27427
telemt_me_reconnect_success_total 17339
telemt_me_reader_eof_total 18633
telemt_me_idle_close_by_peer_total 18632
telemt_me_route_drop_no_conn_total 1389876
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3430259
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13927
telemt_desync_full_logged_total 3673
telemt_desync_suppressed_total 10254
telemt_desync_frames_bucket_total{bucket="1_2"} 3499
telemt_desync_frames_bucket_total{bucket="3_10"} 5276
telemt_desync_frames_bucket_total{bucket="gt_10"} 5152
telemt_pool_swap_total 100
telemt_me_writer_removed_unexpected_total 17893
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 17326
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 554
telemt_user_connections_total{user="hello"} 3430051
telemt_user_connections_current{user="hello"} 1601
telemt_user_octets_from_client{user="hello"} 46899175880 (43.68 GB)
telemt_user_octets_to_client{user="hello"} 1078878310664 (1004.78 GB)
telemt_user_unique_ips_current{user="hello"} 453
telemt_user_unique_ips_recent_window{user="hello"} 258
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 20101.8 (5h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 287944
telemt_connections_bad_total 14894
telemt_handshake_timeouts_total 7712
telemt_upstream_connect_attempt_total 4800
telemt_upstream_connect_success_total 4714
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 4800
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2419
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2246
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 5944
telemt_me_reconnect_success_total 3653
telemt_me_reader_eof_total 3880
telemt_me_idle_close_by_peer_total 3880
telemt_me_route_drop_no_conn_total 104020
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 257902
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 968
telemt_desync_full_logged_total 249
telemt_desync_suppressed_total 719
telemt_desync_frames_bucket_total{bucket="1_2"} 181
telemt_desync_frames_bucket_total{bucket="3_10"} 474
telemt_desync_frames_bucket_total{bucket="gt_10"} 313
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3768
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 3646
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 257926
telemt_user_connections_current{user="hello"} 485
telemt_user_octets_from_client{user="hello"} 2581157696 (2.40 GB)
telemt_user_octets_to_client{user="hello"} 74064587744 (68.98 GB)
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 150058.4 (41h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2772807
telemt_connections_bad_total 27533
telemt_handshake_timeouts_total 183591
telemt_upstream_connect_attempt_total 33708
telemt_upstream_connect_success_total 33698
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 33708
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17469
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16100
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 124
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3270
telemt_me_reconnect_attempts_total 28452
telemt_me_reconnect_success_total 25903
telemt_me_reader_eof_total 27469
telemt_me_idle_close_by_peer_total 27468
telemt_me_route_drop_no_conn_total 936569
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2276698
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8097
telemt_desync_full_logged_total 2678
telemt_desync_suppressed_total 5419
telemt_desync_frames_bucket_total{bucket="1_2"} 1281
telemt_desync_frames_bucket_total{bucket="3_10"} 2950
telemt_desync_frames_bucket_total{bucket="gt_10"} 3866
telemt_pool_swap_total 141
telemt_me_writer_removed_unexpected_total 26204
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 25862
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 301
telemt_user_connections_total{user="hello"} 2276098
telemt_user_connections_current{user="hello"} 945
telemt_user_octets_from_client{user="hello"} 37710538696 (35.12 GB)
telemt_user_octets_to_client{user="hello"} 799183015101 (744.30 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 291
telemt_user_unique_ips_recent_window{user="hello"} 172
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 150058.8 (41h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1766641
telemt_connections_bad_total 18133
telemt_handshake_timeouts_total 135683
telemt_upstream_connect_attempt_total 47367
telemt_upstream_connect_success_total 45037
telemt_upstream_connect_fail_total 2193
telemt_upstream_connect_attempts_per_request{bucket="1"} 47093
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27079
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17867
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2192
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11878
telemt_me_reconnect_attempts_total 40693
telemt_me_reconnect_success_total 31720
telemt_me_reader_eof_total 34071
telemt_me_idle_close_by_peer_total 34064
telemt_me_route_drop_no_conn_total 632947
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1474036
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2964
telemt_desync_full_logged_total 959
telemt_desync_suppressed_total 2005
telemt_desync_frames_bucket_total{bucket="1_2"} 796
telemt_desync_frames_bucket_total{bucket="3_10"} 1226
telemt_desync_frames_bucket_total{bucket="gt_10"} 942
telemt_pool_swap_total 130
telemt_me_writer_removed_unexpected_total 32244
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 31696
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 524
telemt_user_connections_total{user="hello"} 1478747
telemt_user_connections_current{user="hello"} 582
telemt_user_octets_from_client{user="hello"} 23015010613 (21.43 GB)
telemt_user_octets_to_client{user="hello"} 568085313218 (529.07 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 19494.6 (5h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 312060
telemt_connections_bad_total 3992
telemt_handshake_timeouts_total 2886
telemt_upstream_connect_attempt_total 4166
telemt_upstream_connect_success_total 4038
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 4166
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1918
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2116
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_keepalive_timeout_total 77
telemt_me_reconnect_attempts_total 13609
telemt_me_reconnect_success_total 3035
telemt_me_reader_eof_total 3412
telemt_me_idle_close_by_peer_total 3412
telemt_me_route_drop_no_conn_total 123955
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 292381
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 907
telemt_desync_full_logged_total 289
telemt_desync_suppressed_total 618
telemt_desync_frames_bucket_total{bucket="1_2"} 319
telemt_desync_frames_bucket_total{bucket="3_10"} 361
telemt_desync_frames_bucket_total{bucket="gt_10"} 227
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 3380
telemt_me_refill_failed_total 329
telemt_me_writer_restored_same_endpoint_total 3031
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 345
telemt_user_connections_total{user="hello"} 292360
telemt_user_connections_current{user="hello"} 751
telemt_user_octets_from_client{user="hello"} 3363414712 (3.13 GB)
telemt_user_octets_to_client{user="hello"} 92717699724 (86.35 GB)
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 107
```