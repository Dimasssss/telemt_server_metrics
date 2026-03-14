# Server Metrics 2026-03-14 01:48:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 157796.5 (43h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4645333
telemt_connections_bad_total 39797
telemt_handshake_timeouts_total 108236
telemt_upstream_connect_attempt_total 33354
telemt_upstream_connect_success_total 33132
telemt_upstream_connect_fail_total 222
telemt_upstream_connect_attempts_per_request{bucket="1"} 33354
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18093
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14894
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 222
telemt_me_keepalive_timeout_total 6705
telemt_me_reconnect_attempts_total 33060
telemt_me_reconnect_success_total 22922
telemt_me_reader_eof_total 24584
telemt_me_idle_close_by_peer_total 24583
telemt_me_route_drop_no_conn_total 1758753
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4258564
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16711
telemt_desync_full_logged_total 4505
telemt_desync_suppressed_total 12206
telemt_desync_frames_bucket_total{bucket="1_2"} 4175
telemt_desync_frames_bucket_total{bucket="3_10"} 6381
telemt_desync_frames_bucket_total{bucket="gt_10"} 6155
telemt_pool_swap_total 135
telemt_me_writer_removed_unexpected_total 23569
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 22909
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 647
telemt_user_connections_total{user="hello"} 4260420
telemt_user_connections_current{user="hello"} 628
telemt_user_octets_from_client{user="hello"} 62710272648 (58.40 GB)
telemt_user_octets_to_client{user="hello"} 1345685303617 (1.22 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 57460.1 (15h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 684507
telemt_connections_bad_total 50959
telemt_handshake_timeouts_total 13033
telemt_upstream_connect_attempt_total 15970
telemt_upstream_connect_success_total 15720
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 15969
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8800
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6683
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_keepalive_timeout_total 2054
telemt_me_reconnect_attempts_total 14273
telemt_me_reconnect_success_total 10829
telemt_me_reader_eof_total 11494
telemt_me_idle_close_by_peer_total 11493
telemt_me_route_drop_no_conn_total 231140
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 550662
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1651
telemt_desync_full_logged_total 449
telemt_desync_suppressed_total 1202
telemt_desync_frames_bucket_total{bucket="1_2"} 351
telemt_desync_frames_bucket_total{bucket="3_10"} 717
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 11090
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 10821
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 261
telemt_user_connections_total{user="hello"} 552613
telemt_user_connections_current{user="hello"} 155
telemt_user_octets_from_client{user="hello"} 5935857353 (5.53 GB)
telemt_user_octets_to_client{user="hello"} 177925590288 (165.71 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 187417.0 (52h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3361512
telemt_connections_bad_total 34920
telemt_handshake_timeouts_total 223018
telemt_upstream_connect_attempt_total 42146
telemt_upstream_connect_success_total 42125
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 42146
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22111
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19779
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 228
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10408
telemt_me_reconnect_attempts_total 37427
telemt_me_reconnect_success_total 32467
telemt_me_reader_eof_total 34474
telemt_me_idle_close_by_peer_total 34473
telemt_me_route_drop_no_conn_total 1152890
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2795687
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9213
telemt_desync_full_logged_total 3093
telemt_desync_suppressed_total 6120
telemt_desync_frames_bucket_total{bucket="1_2"} 1563
telemt_desync_frames_bucket_total{bucket="3_10"} 3339
telemt_desync_frames_bucket_total{bucket="gt_10"} 4311
telemt_pool_swap_total 176
telemt_me_writer_removed_unexpected_total 32923
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 32426
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 456
telemt_user_connections_total{user="hello"} 2794924
telemt_user_connections_current{user="hello"} 287
telemt_user_octets_from_client{user="hello"} 45052078700 (41.96 GB)
telemt_user_octets_to_client{user="hello"} 998323892821 (929.76 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 187419.5 (52h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2241228
telemt_connections_bad_total 22937
telemt_handshake_timeouts_total 243100
telemt_upstream_connect_attempt_total 58642
telemt_upstream_connect_success_total 56183
telemt_upstream_connect_fail_total 2322
telemt_upstream_connect_attempts_per_request{bucket="1"} 58368
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33607
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22410
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2321
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20406
telemt_me_reconnect_attempts_total 48847
telemt_me_reconnect_success_total 39817
telemt_me_reader_eof_total 42703
telemt_me_idle_close_by_peer_total 42696
telemt_me_route_drop_no_conn_total 769098
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1792764
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3806
telemt_desync_full_logged_total 1223
telemt_desync_suppressed_total 2583
telemt_desync_frames_bucket_total{bucket="1_2"} 1012
telemt_desync_frames_bucket_total{bucket="3_10"} 1588
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 164
telemt_me_writer_removed_unexpected_total 40444
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 39793
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 627
telemt_user_connections_total{user="hello"} 1798685
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 27458628943 (25.57 GB)
telemt_user_octets_to_client{user="hello"} 664989371430 (619.32 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 56852.9 (15h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 688660
telemt_connections_bad_total 7890
telemt_handshake_timeouts_total 8642
telemt_upstream_connect_attempt_total 14306
telemt_upstream_connect_success_total 13906
telemt_upstream_connect_fail_total 400
telemt_upstream_connect_attempts_per_request{bucket="1"} 14306
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6698
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7183
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 400
telemt_me_keepalive_timeout_total 1493
telemt_me_reconnect_attempts_total 43199
telemt_me_reconnect_success_total 11039
telemt_me_reader_eof_total 12320
telemt_me_idle_close_by_peer_total 12319
telemt_me_route_drop_no_conn_total 261035
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 640968
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1646
telemt_desync_full_logged_total 516
telemt_desync_suppressed_total 1130
telemt_desync_frames_bucket_total{bucket="1_2"} 494
telemt_desync_frames_bucket_total{bucket="3_10"} 642
telemt_desync_frames_bucket_total{bucket="gt_10"} 510
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 12141
telemt_me_refill_failed_total 1001
telemt_me_writer_restored_same_endpoint_total 11034
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1102
telemt_user_connections_total{user="hello"} 640861
telemt_user_connections_current{user="hello"} 237
telemt_user_octets_from_client{user="hello"} 10589698200 (9.86 GB)
telemt_user_octets_to_client{user="hello"} 209779278576 (195.37 GB)
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 27
```