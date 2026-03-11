# Server Metrics 2026-03-11 19:22:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 104101.7 (28h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2645340
telemt_connections_bad_total 48650
telemt_handshake_timeouts_total 57994
telemt_upstream_connect_attempt_total 21936
telemt_upstream_connect_success_total 21924
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 21936
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11092
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10722
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5344
telemt_me_reconnect_attempts_total 34544
telemt_me_reconnect_success_total 16654
telemt_me_reader_eof_total 18008
telemt_me_idle_close_by_peer_total 18008
telemt_me_route_drop_no_conn_total 998071
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2418250
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12283
telemt_desync_full_logged_total 3401
telemt_desync_suppressed_total 8882
telemt_desync_frames_bucket_total{bucket="1_2"} 3008
telemt_desync_frames_bucket_total{bucket="3_10"} 4747
telemt_desync_frames_bucket_total{bucket="gt_10"} 4528
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 17401
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 16648
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 747
telemt_user_connections_total{user="hello"} 2416601
telemt_user_connections_current{user="hello"} 1026
telemt_user_octets_from_client{user="hello"} 36104355804 (33.62 GB)
telemt_user_octets_to_client{user="hello"} 685336034196 (638.27 GB)
telemt_user_unique_ips_current{user="hello"} 319
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 104158.2 (28h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 984930
telemt_connections_bad_total 16441
telemt_handshake_timeouts_total 88557
telemt_upstream_connect_attempt_total 32164
telemt_upstream_connect_success_total 29194
telemt_upstream_connect_fail_total 2970
telemt_upstream_connect_attempts_per_request{bucket="1"} 32164
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13776
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13155
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2054
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2970
telemt_me_keepalive_timeout_total 2852
telemt_me_reconnect_attempts_total 23127
telemt_me_reconnect_success_total 21011
telemt_me_reader_eof_total 22247
telemt_me_idle_close_by_peer_total 22244
telemt_me_route_drop_no_conn_total 372166
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 821679
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3251
telemt_desync_full_logged_total 1056
telemt_desync_suppressed_total 2195
telemt_desync_frames_bucket_total{bucket="1_2"} 1031
telemt_desync_frames_bucket_total{bucket="3_10"} 1158
telemt_desync_frames_bucket_total{bucket="gt_10"} 1062
telemt_pool_swap_total 84
telemt_me_writer_removed_unexpected_total 21309
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 20988
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 298
telemt_user_connections_total{user="hello"} 824125
telemt_user_connections_current{user="hello"} 434
telemt_user_octets_from_client{user="hello"} 9881409890 (9.20 GB)
telemt_user_octets_to_client{user="hello"} 238037180344 (221.69 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 104158.2 (28h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1696148
telemt_connections_bad_total 10609
telemt_handshake_timeouts_total 133787
telemt_upstream_connect_attempt_total 26888
telemt_upstream_connect_success_total 26552
telemt_upstream_connect_fail_total 336
telemt_upstream_connect_attempts_per_request{bucket="1"} 26888
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14348
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12068
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 135
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 336
telemt_me_keepalive_timeout_total 1985
telemt_me_reconnect_attempts_total 51218
telemt_me_reconnect_success_total 20219
telemt_me_reader_eof_total 22047
telemt_me_idle_close_by_peer_total 22047
telemt_me_route_drop_no_conn_total 618544
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1487583
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4110
telemt_desync_full_logged_total 1209
telemt_desync_suppressed_total 2901
telemt_desync_frames_bucket_total{bucket="1_2"} 959
telemt_desync_frames_bucket_total{bucket="3_10"} 1559
telemt_desync_frames_bucket_total{bucket="gt_10"} 1592
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 21467
telemt_me_refill_failed_total 963
telemt_me_writer_restored_same_endpoint_total 20207
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1248
telemt_user_connections_total{user="hello"} 1487245
telemt_user_connections_current{user="hello"} 676
telemt_user_octets_from_client{user="hello"} 19224271757 (17.90 GB)
telemt_user_octets_to_client{user="hello"} 453708338685 (422.55 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 104158.6 (28h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1212623
telemt_connections_bad_total 78201
telemt_handshake_timeouts_total 110616
telemt_upstream_connect_attempt_total 28156
telemt_upstream_connect_success_total 28156
telemt_upstream_connect_attempts_per_request{bucket="1"} 28156
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15356
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12794
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1439
telemt_me_reconnect_attempts_total 27563
telemt_me_reconnect_success_total 22948
telemt_me_reader_eof_total 24362
telemt_me_idle_close_by_peer_total 24361
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 404680
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 988775
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2114
telemt_desync_full_logged_total 800
telemt_desync_suppressed_total 1314
telemt_desync_frames_bucket_total{bucket="1_2"} 759
telemt_desync_frames_bucket_total{bucket="3_10"} 718
telemt_desync_frames_bucket_total{bucket="gt_10"} 637
telemt_pool_swap_total 84
telemt_me_writer_removed_unexpected_total 23333
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 22915
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 385
telemt_user_connections_total{user="hello"} 988033
telemt_user_connections_current{user="hello"} 496
telemt_user_octets_from_client{user="hello"} 11711906348 (10.91 GB)
telemt_user_octets_to_client{user="hello"} 299649252688 (279.07 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 8834.7 (2h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139681
telemt_connections_bad_total 647
telemt_handshake_timeouts_total 944
telemt_upstream_connect_attempt_total 2627
telemt_upstream_connect_success_total 2626
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2627
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1370
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1241
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 57
telemt_me_reconnect_attempts_total 2158
telemt_me_reconnect_success_total 2138
telemt_me_reader_eof_total 2175
telemt_me_idle_close_by_peer_total 2175
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 49022
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 128768
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 256
telemt_desync_full_logged_total 82
telemt_desync_suppressed_total 174
telemt_desync_frames_bucket_total{bucket="1_2"} 64
telemt_desync_frames_bucket_total{bucket="3_10"} 85
telemt_desync_frames_bucket_total{bucket="gt_10"} 107
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 2163
telemt_me_writer_restored_same_endpoint_total 2114
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 128735
telemt_user_connections_current{user="hello"} 582
telemt_user_octets_from_client{user="hello"} 6583689548 (6.13 GB)
telemt_user_octets_to_client{user="hello"} 43941875680 (40.92 GB)
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 79
```