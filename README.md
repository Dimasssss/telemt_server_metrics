# Server Metrics 2026-03-11 16:38:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 94299.8 (26h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2354550
telemt_connections_bad_total 41014
telemt_handshake_timeouts_total 53947
telemt_upstream_connect_attempt_total 19692
telemt_upstream_connect_success_total 19680
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 19692
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9911
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9674
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5064
telemt_me_reconnect_attempts_total 32788
telemt_me_reconnect_success_total 14913
telemt_me_reader_eof_total 16176
telemt_me_idle_close_by_peer_total 16176
telemt_me_route_drop_no_conn_total 873346
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2154228
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11200
telemt_desync_full_logged_total 3055
telemt_desync_suppressed_total 8145
telemt_desync_frames_bucket_total{bucket="1_2"} 2770
telemt_desync_frames_bucket_total{bucket="3_10"} 4320
telemt_desync_frames_bucket_total{bucket="gt_10"} 4110
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 15637
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 14907
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 724
telemt_user_connections_total{user="hello"} 2152681
telemt_user_connections_current{user="hello"} 1384
telemt_user_octets_from_client{user="hello"} 29004852476 (27.01 GB)
telemt_user_octets_to_client{user="hello"} 607191724760 (565.49 GB)
telemt_user_unique_ips_current{user="hello"} 387
telemt_user_unique_ips_recent_window{user="hello"} 164
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 94356.5 (26h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 882352
telemt_connections_bad_total 15358
telemt_handshake_timeouts_total 71514
telemt_upstream_connect_attempt_total 29708
telemt_upstream_connect_success_total 26748
telemt_upstream_connect_fail_total 2960
telemt_upstream_connect_attempts_per_request{bucket="1"} 29708
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12509
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11991
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2960
telemt_me_keepalive_timeout_total 2652
telemt_me_reconnect_attempts_total 21167
telemt_me_reconnect_success_total 19068
telemt_me_reader_eof_total 20176
telemt_me_idle_close_by_peer_total 20173
telemt_me_route_drop_no_conn_total 338792
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 740017
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2968
telemt_desync_full_logged_total 948
telemt_desync_suppressed_total 2020
telemt_desync_frames_bucket_total{bucket="1_2"} 909
telemt_desync_frames_bucket_total{bucket="3_10"} 1067
telemt_desync_frames_bucket_total{bucket="gt_10"} 992
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 19339
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 19045
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 271
telemt_user_connections_total{user="hello"} 742477
telemt_user_connections_current{user="hello"} 520
telemt_user_octets_from_client{user="hello"} 8444759342 (7.86 GB)
telemt_user_octets_to_client{user="hello"} 209902812552 (195.49 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 94356.3 (26h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1508236
telemt_connections_bad_total 8918
telemt_handshake_timeouts_total 125705
telemt_upstream_connect_attempt_total 24332
telemt_upstream_connect_success_total 24024
telemt_upstream_connect_fail_total 308
telemt_upstream_connect_attempts_per_request{bucket="1"} 24332
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12967
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10932
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 308
telemt_me_keepalive_timeout_total 1751
telemt_me_reconnect_attempts_total 41954
telemt_me_reconnect_success_total 18200
telemt_me_reader_eof_total 19754
telemt_me_idle_close_by_peer_total 19754
telemt_me_route_drop_no_conn_total 551641
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1318605
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3451
telemt_desync_full_logged_total 1021
telemt_desync_suppressed_total 2430
telemt_desync_frames_bucket_total{bucket="1_2"} 860
telemt_desync_frames_bucket_total{bucket="3_10"} 1302
telemt_desync_frames_bucket_total{bucket="gt_10"} 1289
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 19189
telemt_me_refill_failed_total 737
telemt_me_writer_restored_same_endpoint_total 18188
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 989
telemt_user_connections_total{user="hello"} 1318310
telemt_user_connections_current{user="hello"} 774
telemt_user_octets_from_client{user="hello"} 15954547001 (14.86 GB)
telemt_user_octets_to_client{user="hello"} 399019112701 (371.62 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 220
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 94356.7 (26h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1087565
telemt_connections_bad_total 77985
telemt_handshake_timeouts_total 104943
telemt_upstream_connect_attempt_total 25392
telemt_upstream_connect_success_total 25391
telemt_upstream_connect_attempts_per_request{bucket="1"} 25391
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13876
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11510
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1144
telemt_me_reconnect_attempts_total 21770
telemt_me_reconnect_success_total 20691
telemt_me_reader_eof_total 21917
telemt_me_idle_close_by_peer_total 21916
telemt_me_seq_mismatch_total 20
telemt_me_route_drop_no_conn_total 356890
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 871686
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 31
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1815
telemt_desync_full_logged_total 701
telemt_desync_suppressed_total 1114
telemt_desync_frames_bucket_total{bucket="1_2"} 656
telemt_desync_frames_bucket_total{bucket="3_10"} 638
telemt_desync_frames_bucket_total{bucket="gt_10"} 521
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 20946
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 20660
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 255
telemt_user_connections_total{user="hello"} 870992
telemt_user_connections_current{user="hello"} 594
telemt_user_octets_from_client{user="hello"} 10450759572 (9.73 GB)
telemt_user_octets_to_client{user="hello"} 257155914664 (239.50 GB)
telemt_user_unique_ips_current{user="hello"} 168
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 94356.5 (26h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1199454
telemt_connections_bad_total 6957
telemt_handshake_timeouts_total 11867
telemt_upstream_connect_attempt_total 25728
telemt_upstream_connect_success_total 25614
telemt_upstream_connect_fail_total 114
telemt_upstream_connect_attempts_per_request{bucket="1"} 25728
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13088
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12319
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 202
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 114
telemt_me_keepalive_timeout_total 2146
telemt_me_reconnect_attempts_total 24864
telemt_me_reconnect_success_total 20767
telemt_me_reader_eof_total 21881
telemt_me_idle_close_by_peer_total 21881
telemt_me_route_drop_no_conn_total 428147
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1092785
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4268
telemt_desync_full_logged_total 1523
telemt_desync_suppressed_total 2745
telemt_desync_frames_bucket_total{bucket="1_2"} 1409
telemt_desync_frames_bucket_total{bucket="3_10"} 1592
telemt_desync_frames_bucket_total{bucket="gt_10"} 1267
telemt_pool_swap_total 61
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 21167
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 20767
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 400
telemt_user_connections_total{user="hello"} 1092484
telemt_user_connections_current{user="hello"} 686
telemt_user_octets_from_client{user="hello"} 20463912703 (19.06 GB)
telemt_user_octets_to_client{user="hello"} 378964465734 (352.94 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 107
```