# Server Metrics 2026-03-11 03:08:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 45685.2 (12h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 882868
telemt_connections_bad_total 10065
telemt_handshake_timeouts_total 19150
telemt_upstream_connect_attempt_total 9890
telemt_upstream_connect_success_total 9881
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 9890
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4948
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4873
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 513
telemt_me_reconnect_attempts_total 19218
telemt_me_reconnect_success_total 7547
telemt_me_reader_eof_total 8239
telemt_me_idle_close_by_peer_total 8239
telemt_me_route_drop_no_conn_total 348582
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 820438
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3808
telemt_desync_full_logged_total 1058
telemt_desync_suppressed_total 2750
telemt_desync_frames_bucket_total{bucket="1_2"} 1096
telemt_desync_frames_bucket_total{bucket="3_10"} 1430
telemt_desync_frames_bucket_total{bucket="gt_10"} 1282
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 7978
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 7541
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 431
telemt_user_connections_total{user="hello"} 820169
telemt_user_connections_current{user="hello"} 546
telemt_user_octets_from_client{user="hello"} 11041024016 (10.28 GB)
telemt_user_octets_to_client{user="hello"} 243729817188 (226.99 GB)
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 45741.9 (12h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 366835
telemt_connections_bad_total 2414
telemt_handshake_timeouts_total 18350
telemt_upstream_connect_attempt_total 17811
telemt_upstream_connect_success_total 14920
telemt_upstream_connect_fail_total 2891
telemt_upstream_connect_attempts_per_request{bucket="1"} 17811
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6580
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6099
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2032
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2891
telemt_me_keepalive_timeout_total 1755
telemt_me_reconnect_attempts_total 10489
telemt_me_reconnect_success_total 9672
telemt_me_reader_eof_total 10207
telemt_me_idle_close_by_peer_total 10205
telemt_me_route_drop_no_conn_total 179193
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 314689
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1797
telemt_desync_full_logged_total 519
telemt_desync_suppressed_total 1278
telemt_desync_frames_bucket_total{bucket="1_2"} 552
telemt_desync_frames_bucket_total{bucket="3_10"} 640
telemt_desync_frames_bucket_total{bucket="gt_10"} 605
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 9789
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 9651
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 316959
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 2992798622 (2.79 GB)
telemt_user_octets_to_client{user="hello"} 74636630824 (69.51 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 45741.8 (12h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 614880
telemt_connections_bad_total 5335
telemt_handshake_timeouts_total 34750
telemt_upstream_connect_attempt_total 12405
telemt_upstream_connect_success_total 12242
telemt_upstream_connect_fail_total 163
telemt_upstream_connect_attempts_per_request{bucket="1"} 12405
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6727
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5442
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 163
telemt_me_keepalive_timeout_total 541
telemt_me_reconnect_attempts_total 19934
telemt_me_reconnect_success_total 8866
telemt_me_reader_eof_total 9624
telemt_me_idle_close_by_peer_total 9624
telemt_me_route_drop_no_conn_total 208594
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 545816
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1598
telemt_desync_full_logged_total 470
telemt_desync_suppressed_total 1128
telemt_desync_frames_bucket_total{bucket="1_2"} 350
telemt_desync_frames_bucket_total{bucket="3_10"} 555
telemt_desync_frames_bucket_total{bucket="gt_10"} 693
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 9331
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 8855
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 465
telemt_user_connections_total{user="hello"} 546710
telemt_user_connections_current{user="hello"} 322
telemt_user_octets_from_client{user="hello"} 7073465637 (6.59 GB)
telemt_user_octets_to_client{user="hello"} 166584206609 (155.14 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 45742.1 (12h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 462241
telemt_connections_bad_total 43212
telemt_handshake_timeouts_total 45040
telemt_upstream_connect_attempt_total 13300
telemt_upstream_connect_success_total 13300
telemt_upstream_connect_attempts_per_request{bucket="1"} 13300
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7500
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5797
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 464
telemt_me_reconnect_attempts_total 12039
telemt_me_reconnect_success_total 11001
telemt_me_reader_eof_total 11670
telemt_me_idle_close_by_peer_total 11670
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 138220
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 360294
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 768
telemt_desync_full_logged_total 306
telemt_desync_suppressed_total 462
telemt_desync_frames_bucket_total{bucket="1_2"} 289
telemt_desync_frames_bucket_total{bucket="3_10"} 269
telemt_desync_frames_bucket_total{bucket="gt_10"} 210
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 11133
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 10982
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 359962
telemt_user_connections_current{user="hello"} 222
telemt_user_octets_from_client{user="hello"} 4383809220 (4.08 GB)
telemt_user_octets_to_client{user="hello"} 96122267340 (89.52 GB)
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 45741.8 (12h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 487529
telemt_connections_bad_total 5810
telemt_handshake_timeouts_total 3053
telemt_upstream_connect_attempt_total 13417
telemt_upstream_connect_success_total 13360
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 13417
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6887
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6352
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 536
telemt_me_reconnect_attempts_total 14798
telemt_me_reconnect_success_total 11021
telemt_me_reader_eof_total 11624
telemt_me_idle_close_by_peer_total 11624
telemt_me_route_drop_no_conn_total 156914
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 444134
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2330
telemt_desync_full_logged_total 907
telemt_desync_suppressed_total 1423
telemt_desync_frames_bucket_total{bucket="1_2"} 862
telemt_desync_frames_bucket_total{bucket="3_10"} 992
telemt_desync_frames_bucket_total{bucket="gt_10"} 476
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 11280
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 11021
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 259
telemt_user_connections_total{user="hello"} 443790
telemt_user_connections_current{user="hello"} 245
telemt_user_octets_from_client{user="hello"} 8578302016 (7.99 GB)
telemt_user_octets_to_client{user="hello"} 160957816672 (149.90 GB)
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 40
```