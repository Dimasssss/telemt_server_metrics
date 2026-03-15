# Server Metrics 2026-03-15 18:10:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 71740.3 (19h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2557109
telemt_connections_bad_total 150992
telemt_handshake_timeouts_total 33428
telemt_upstream_connect_attempt_total 13875
telemt_upstream_connect_success_total 13816
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 13875
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7161
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6581
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 15130
telemt_me_reconnect_success_total 10231
telemt_me_reader_eof_total 10935
telemt_me_idle_close_by_peer_total 10935
telemt_me_route_drop_no_conn_total 885548
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2134530
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8282
telemt_desync_full_logged_total 2262
telemt_desync_suppressed_total 6020
telemt_desync_frames_bucket_total{bucket="1_2"} 2048
telemt_desync_frames_bucket_total{bucket="3_10"} 3157
telemt_desync_frames_bucket_total{bucket="gt_10"} 3077
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 10556
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 10220
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 325
telemt_user_connections_total{user="hello"} 2134003
telemt_user_connections_current{user="hello"} 2501
telemt_user_octets_from_client{user="hello"} 32122369004 (29.92 GB)
telemt_user_octets_to_client{user="hello"} 813154852488 (757.31 GB)
telemt_user_unique_ips_current{user="hello"} 678
telemt_user_unique_ips_recent_window{user="hello"} 291
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 71741.3 (19h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 989322
telemt_connections_bad_total 56275
telemt_handshake_timeouts_total 63314
telemt_upstream_connect_attempt_total 17815
telemt_upstream_connect_success_total 17719
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 17815
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9398
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8144
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 40
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 137
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 14987
telemt_me_reconnect_success_total 13776
telemt_me_reader_eof_total 14578
telemt_me_idle_close_by_peer_total 14578
telemt_me_route_drop_no_conn_total 256739
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 764461
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2223
telemt_desync_full_logged_total 754
telemt_desync_suppressed_total 1469
telemt_desync_frames_bucket_total{bucket="1_2"} 778
telemt_desync_frames_bucket_total{bucket="3_10"} 838
telemt_desync_frames_bucket_total{bucket="gt_10"} 607
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 13994
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 13764
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 218
telemt_user_connections_total{user="hello"} 764690
telemt_user_connections_current{user="hello"} 858
telemt_user_octets_from_client{user="hello"} 11062731099 (10.30 GB)
telemt_user_octets_to_client{user="hello"} 287531845588 (267.78 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 260
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 71741.4 (19h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2176772
telemt_connections_bad_total 50785
telemt_handshake_timeouts_total 215141
telemt_upstream_connect_attempt_total 15425
telemt_upstream_connect_success_total 15348
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 15425
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7928
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7343
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 77
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 13003
telemt_me_reconnect_success_total 11734
telemt_me_reader_eof_total 12431
telemt_me_idle_close_by_peer_total 12431
telemt_me_route_drop_no_conn_total 566316
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1360698
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3536
telemt_desync_full_logged_total 1273
telemt_desync_suppressed_total 2263
telemt_desync_frames_bucket_total{bucket="1_2"} 807
telemt_desync_frames_bucket_total{bucket="3_10"} 1377
telemt_desync_frames_bucket_total{bucket="gt_10"} 1352
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 11939
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 11715
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 205
telemt_user_connections_total{user="hello"} 1356581
telemt_user_connections_current{user="hello"} 1430
telemt_user_octets_from_client{user="hello"} 25240020392 (23.51 GB)
telemt_user_octets_to_client{user="hello"} 505994037256 (471.24 GB)
telemt_user_unique_ips_current{user="hello"} 430
telemt_user_unique_ips_recent_window{user="hello"} 211
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 71741.2 (19h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1052996
telemt_connections_bad_total 82066
telemt_handshake_timeouts_total 51580
telemt_upstream_connect_attempt_total 170829
telemt_upstream_connect_success_total 170229
telemt_upstream_connect_fail_total 600
telemt_upstream_connect_attempts_per_request{bucket="1"} 170829
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 156830
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13339
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 600
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 61740
telemt_me_reconnect_success_total 13675
telemt_me_reader_eof_total 15541
telemt_me_idle_close_by_peer_total 15541
telemt_me_seq_mismatch_total 27
telemt_me_route_drop_no_conn_total 250603
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 667741
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 44
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1868
telemt_desync_full_logged_total 512
telemt_desync_suppressed_total 1356
telemt_desync_frames_bucket_total{bucket="1_2"} 479
telemt_desync_frames_bucket_total{bucket="3_10"} 720
telemt_desync_frames_bucket_total{bucket="gt_10"} 669
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 15321
telemt_me_refill_failed_total 1504
telemt_me_writer_restored_same_endpoint_total 13639
telemt_me_writer_restored_fallback_total 36
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1646
telemt_user_connections_total{user="hello"} 820254
telemt_user_connections_current{user="hello"} 924
telemt_user_octets_from_client{user="hello"} 15232893777 (14.19 GB)
telemt_user_octets_to_client{user="hello"} 292473461640 (272.39 GB)
telemt_user_msgs_from_client{user="hello"} 3035962
telemt_user_msgs_to_client{user="hello"} 10927629
telemt_user_unique_ips_current{user="hello"} 248
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 71742.3 (19h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1069431
telemt_connections_bad_total 12593
telemt_handshake_timeouts_total 23386
telemt_upstream_connect_attempt_total 15744
telemt_upstream_connect_success_total 15660
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 15744
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7250
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8390
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 88
telemt_me_reconnect_attempts_total 15763
telemt_me_reconnect_success_total 12068
telemt_me_reader_eof_total 12872
telemt_me_idle_close_by_peer_total 12872
telemt_me_route_drop_no_conn_total 270831
telemt_me_route_drop_channel_closed_total 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 886827
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3079
telemt_desync_full_logged_total 1017
telemt_desync_suppressed_total 2062
telemt_desync_frames_bucket_total{bucket="1_2"} 935
telemt_desync_frames_bucket_total{bucket="3_10"} 1141
telemt_desync_frames_bucket_total{bucket="gt_10"} 1003
telemt_pool_swap_total 60
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 12329
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 12060
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 261
telemt_user_connections_total{user="hello"} 886850
telemt_user_connections_current{user="hello"} 1006
telemt_user_octets_from_client{user="hello"} 10957249732 (10.20 GB)
telemt_user_octets_to_client{user="hello"} 310002892780 (288.71 GB)
telemt_user_unique_ips_current{user="hello"} 261
telemt_user_unique_ips_recent_window{user="hello"} 119
```