# Server Metrics 2026-03-14 12:38:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 196778.4 (54h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5716094
telemt_connections_bad_total 63562
telemt_handshake_timeouts_total 126154
telemt_upstream_connect_attempt_total 41301
telemt_upstream_connect_success_total 41038
telemt_upstream_connect_fail_total 263
telemt_upstream_connect_attempts_per_request{bucket="1"} 41301
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22226
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18652
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 160
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 263
telemt_me_keepalive_timeout_total 7866
telemt_me_reconnect_attempts_total 46474
telemt_me_reconnect_success_total 28913
telemt_me_reader_eof_total 31133
telemt_me_idle_close_by_peer_total 31132
telemt_me_route_drop_no_conn_total 2166453
telemt_me_route_drop_channel_closed_total 31
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5241360
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 20236
telemt_desync_full_logged_total 5540
telemt_desync_suppressed_total 14696
telemt_desync_frames_bucket_total{bucket="1_2"} 4881
telemt_desync_frames_bucket_total{bucket="3_10"} 7695
telemt_desync_frames_bucket_total{bucket="gt_10"} 7660
telemt_pool_swap_total 164
telemt_me_writer_removed_unexpected_total 29882
telemt_me_refill_failed_total 543
telemt_me_writer_restored_same_endpoint_total 28900
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 969
telemt_user_connections_total{user="hello"} 5242925
telemt_user_connections_current{user="hello"} 1767
telemt_user_octets_from_client{user="hello"} 81663773396 (76.06 GB)
telemt_user_octets_to_client{user="hello"} 1669018983961 (1.52 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 480
telemt_user_unique_ips_recent_window{user="hello"} 222
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 96442.3 (26h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1112085
telemt_connections_bad_total 58964
telemt_handshake_timeouts_total 26001
telemt_upstream_connect_attempt_total 24683
telemt_upstream_connect_success_total 24376
telemt_upstream_connect_fail_total 307
telemt_upstream_connect_attempts_per_request{bucket="1"} 24683
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13272
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10792
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 48
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 264
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 307
telemt_me_keepalive_timeout_total 2420
telemt_me_reconnect_attempts_total 37130
telemt_me_reconnect_success_total 17520
telemt_me_reader_eof_total 19023
telemt_me_idle_close_by_peer_total 19022
telemt_me_route_drop_no_conn_total 376675
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 917452
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2548
telemt_desync_full_logged_total 803
telemt_desync_suppressed_total 1745
telemt_desync_frames_bucket_total{bucket="1_2"} 662
telemt_desync_frames_bucket_total{bucket="3_10"} 1059
telemt_desync_frames_bucket_total{bucket="gt_10"} 827
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 18379
telemt_me_refill_failed_total 606
telemt_me_writer_restored_same_endpoint_total 17512
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 859
telemt_user_connections_total{user="hello"} 919363
telemt_user_connections_current{user="hello"} 625
telemt_user_octets_from_client{user="hello"} 10136838513 (9.44 GB)
telemt_user_octets_to_client{user="hello"} 325983950364 (303.60 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 226398.9 (62h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4052975
telemt_connections_bad_total 46569
telemt_handshake_timeouts_total 279928
telemt_upstream_connect_attempt_total 50948
telemt_upstream_connect_success_total 50927
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 50948
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26871
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23790
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 259
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 11283
telemt_me_reconnect_attempts_total 45332
telemt_me_reconnect_success_total 39326
telemt_me_reader_eof_total 41768
telemt_me_idle_close_by_peer_total 41766
telemt_me_route_drop_no_conn_total 1393223
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3389956
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10847
telemt_desync_full_logged_total 3662
telemt_desync_suppressed_total 7185
telemt_desync_frames_bucket_total{bucket="1_2"} 1991
telemt_desync_frames_bucket_total{bucket="3_10"} 3908
telemt_desync_frames_bucket_total{bucket="gt_10"} 4948
telemt_pool_swap_total 209
telemt_pool_stale_pick_total 5
telemt_me_writer_removed_unexpected_total 39909
telemt_me_refill_failed_total 180
telemt_me_writer_restored_same_endpoint_total 39285
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 583
telemt_user_connections_total{user="hello"} 3389093
telemt_user_connections_current{user="hello"} 940
telemt_user_octets_from_client{user="hello"} 57847790368 (53.87 GB)
telemt_user_octets_to_client{user="hello"} 1208494835649 (1.10 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 277
telemt_user_unique_ips_recent_window{user="hello"} 143
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 226401.5 (62h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2644061
telemt_connections_bad_total 23515
telemt_handshake_timeouts_total 342825
telemt_upstream_connect_attempt_total 69757
telemt_upstream_connect_success_total 67248
telemt_upstream_connect_fail_total 2372
telemt_upstream_connect_attempts_per_request{bucket="1"} 69483
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40007
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27075
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2371
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20999
telemt_me_reconnect_attempts_total 61731
telemt_me_reconnect_success_total 48947
telemt_me_reader_eof_total 52437
telemt_me_idle_close_by_peer_total 52429
telemt_me_route_drop_no_conn_total 877530
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2065685
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4117
telemt_desync_full_logged_total 1355
telemt_desync_suppressed_total 2762
telemt_desync_frames_bucket_total{bucket="1_2"} 1171
telemt_desync_frames_bucket_total{bucket="3_10"} 1683
telemt_desync_frames_bucket_total{bucket="gt_10"} 1263
telemt_pool_swap_total 194
telemt_me_writer_removed_unexpected_total 49773
telemt_me_refill_failed_total 389
telemt_me_writer_restored_same_endpoint_total 48922
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 826
telemt_user_connections_total{user="hello"} 2072174
telemt_user_connections_current{user="hello"} 400
telemt_user_octets_from_client{user="hello"} 30643394951 (28.54 GB)
telemt_user_octets_to_client{user="hello"} 736562405610 (685.98 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 95834.9 (26h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1100034
telemt_connections_bad_total 18129
telemt_handshake_timeouts_total 14155
telemt_upstream_connect_attempt_total 23022
telemt_upstream_connect_success_total 22369
telemt_upstream_connect_fail_total 653
telemt_upstream_connect_attempts_per_request{bucket="1"} 23022
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10728
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11615
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 653
telemt_me_keepalive_timeout_total 1818
telemt_me_reconnect_attempts_total 86752
telemt_me_reconnect_success_total 17586
telemt_me_reader_eof_total 20155
telemt_me_idle_close_by_peer_total 20154
telemt_me_route_drop_no_conn_total 443954
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1019269
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2719
telemt_desync_full_logged_total 853
telemt_desync_suppressed_total 1866
telemt_desync_frames_bucket_total{bucket="1_2"} 985
telemt_desync_frames_bucket_total{bucket="3_10"} 951
telemt_desync_frames_bucket_total{bucket="gt_10"} 783
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 19906
telemt_me_refill_failed_total 2156
telemt_me_writer_restored_same_endpoint_total 17581
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 2320
telemt_user_connections_total{user="hello"} 1018467
telemt_user_connections_current{user="hello"} 774
telemt_user_octets_from_client{user="hello"} 17711101880 (16.49 GB)
telemt_user_octets_to_client{user="hello"} 343539536576 (319.95 GB)
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 89
```