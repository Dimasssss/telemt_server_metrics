# Server Metrics 2026-03-14 08:48:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 182960.7 (50h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5187022
telemt_connections_bad_total 45362
telemt_handshake_timeouts_total 116786
telemt_upstream_connect_attempt_total 38481
telemt_upstream_connect_success_total 38231
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 38481
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20722
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17356
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 153
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_keepalive_timeout_total 7420
telemt_me_reconnect_attempts_total 38002
telemt_me_reconnect_success_total 26790
telemt_me_reader_eof_total 28755
telemt_me_idle_close_by_peer_total 28754
telemt_me_route_drop_no_conn_total 1963381
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4756847
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 18186
telemt_desync_full_logged_total 4957
telemt_desync_suppressed_total 13229
telemt_desync_frames_bucket_total{bucket="1_2"} 4508
telemt_desync_frames_bucket_total{bucket="3_10"} 6913
telemt_desync_frames_bucket_total{bucket="gt_10"} 6765
telemt_pool_swap_total 159
telemt_me_writer_removed_unexpected_total 27530
telemt_me_refill_failed_total 345
telemt_me_writer_restored_same_endpoint_total 26777
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 740
telemt_user_connections_total{user="hello"} 4758297
telemt_user_connections_current{user="hello"} 1614
telemt_user_octets_from_client{user="hello"} 72904373836 (67.90 GB)
telemt_user_octets_to_client{user="hello"} 1521818068801 (1.38 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 457
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 82624.7 (22h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 911287
telemt_connections_bad_total 54151
telemt_handshake_timeouts_total 17641
telemt_upstream_connect_attempt_total 22127
telemt_upstream_connect_success_total 21846
telemt_upstream_connect_fail_total 281
telemt_upstream_connect_attempts_per_request{bucket="1"} 22127
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11884
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9680
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 39
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 243
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 281
telemt_me_keepalive_timeout_total 2180
telemt_me_reconnect_attempts_total 21554
telemt_me_reconnect_success_total 15716
telemt_me_reader_eof_total 16745
telemt_me_idle_close_by_peer_total 16744
telemt_me_route_drop_no_conn_total 303356
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 737821
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
telemt_me_writer_removed_unexpected_total 16124
telemt_me_refill_failed_total 176
telemt_me_writer_restored_same_endpoint_total 15708
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 408
telemt_user_connections_total{user="hello"} 739719
telemt_user_connections_current{user="hello"} 550
telemt_user_octets_from_client{user="hello"} 7837185633 (7.30 GB)
telemt_user_octets_to_client{user="hello"} 256757228976 (239.12 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 212581.4 (59h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3704993
telemt_connections_bad_total 44028
telemt_handshake_timeouts_total 244455
telemt_upstream_connect_attempt_total 47966
telemt_upstream_connect_success_total 47945
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 47966
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25333
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22359
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 246
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10793
telemt_me_reconnect_attempts_total 42028
telemt_me_reconnect_success_total 37039
telemt_me_reader_eof_total 39330
telemt_me_idle_close_by_peer_total 39329
telemt_me_route_drop_no_conn_total 1271486
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3092353
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10104
telemt_desync_full_logged_total 3428
telemt_desync_suppressed_total 6676
telemt_desync_frames_bucket_total{bucket="1_2"} 1786
telemt_desync_frames_bucket_total{bucket="3_10"} 3664
telemt_desync_frames_bucket_total{bucket="gt_10"} 4654
telemt_pool_swap_total 200
telemt_me_writer_removed_unexpected_total 37552
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 36998
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 513
telemt_user_connections_total{user="hello"} 3091500
telemt_user_connections_current{user="hello"} 834
telemt_user_octets_from_client{user="hello"} 52457520528 (48.85 GB)
telemt_user_octets_to_client{user="hello"} 1104704523229 (1.00 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 262
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 212583.8 (59h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2455463
telemt_connections_bad_total 23350
telemt_handshake_timeouts_total 300288
telemt_upstream_connect_attempt_total 66142
telemt_upstream_connect_success_total 63644
telemt_upstream_connect_fail_total 2361
telemt_upstream_connect_attempts_per_request{bucket="1"} 65868
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37995
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25483
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2360
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20583
telemt_me_reconnect_attempts_total 55820
telemt_me_reconnect_success_total 46030
telemt_me_reader_eof_total 49305
telemt_me_idle_close_by_peer_total 49298
telemt_me_route_drop_no_conn_total 822639
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1930643
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3970
telemt_desync_full_logged_total 1295
telemt_desync_suppressed_total 2675
telemt_desync_frames_bucket_total{bucket="1_2"} 1099
telemt_desync_frames_bucket_total{bucket="3_10"} 1630
telemt_desync_frames_bucket_total{bucket="gt_10"} 1241
telemt_pool_swap_total 186
telemt_me_writer_removed_unexpected_total 46729
telemt_me_refill_failed_total 297
telemt_me_writer_restored_same_endpoint_total 46006
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 699
telemt_user_connections_total{user="hello"} 1936789
telemt_user_connections_current{user="hello"} 408
telemt_user_octets_from_client{user="hello"} 28981768395 (26.99 GB)
telemt_user_octets_to_client{user="hello"} 703764201862 (655.43 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 82017.3 (22h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 895458
telemt_connections_bad_total 11388
telemt_handshake_timeouts_total 10866
telemt_upstream_connect_attempt_total 20652
telemt_upstream_connect_success_total 20097
telemt_upstream_connect_fail_total 555
telemt_upstream_connect_attempts_per_request{bucket="1"} 20652
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9628
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10443
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 555
telemt_me_keepalive_timeout_total 1637
telemt_me_reconnect_attempts_total 66529
telemt_me_reconnect_success_total 15995
telemt_me_reader_eof_total 17971
telemt_me_idle_close_by_peer_total 17970
telemt_me_route_drop_no_conn_total 341712
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 833653
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2151
telemt_desync_full_logged_total 676
telemt_desync_suppressed_total 1475
telemt_desync_frames_bucket_total{bucket="1_2"} 693
telemt_desync_frames_bucket_total{bucket="3_10"} 815
telemt_desync_frames_bucket_total{bucket="gt_10"} 643
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 17717
telemt_me_refill_failed_total 1574
telemt_me_writer_restored_same_endpoint_total 15990
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1722
telemt_user_connections_total{user="hello"} 833519
telemt_user_connections_current{user="hello"} 690
telemt_user_octets_from_client{user="hello"} 15096995932 (14.06 GB)
telemt_user_octets_to_client{user="hello"} 283426970488 (263.96 GB)
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 95
```